---
name: hebrew-dataset-sweep
description: Sweep Hugging Face for Hebrew datasets (speech/audio, sentence, text corpora, translation, NLP tasks) with the saved searches in hfsearches.json, keep a dated firehose snapshot, triage each new dataset as Hebrew-specific vs multilingual-with-Hebrew, and update the README. Use on "sweep Hebrew datasets", "update the datasets list", "new Hebrew audio datasets", "trending Hebrew datasets".
---

# Hebrew dataset sweep

Companion to `hebrew-model-sweep` in [Hebrew-AI-Models](https://github.com/danielrosehill/Hebrew-AI-Models); same tooling, `scripts/*.py` byte-identical (copy any change to the other repo). Files:

- `hfsearches.json` (`kind: datasets`): the Hebrew language tag (`language:he`) plus a task category plus a sort; the `all-name` search matches dataset ids containing `heb` with no task filter, because many Hebrew datasets set no task category. `web_url` opens the same search in a browser.
- `collections.json`: the maintainer's curated collections, imported with skill `import-collections`.
- `scripts/snapshot.py`: writes `snapshots/YYYY-MM-DD/` (raw `<search-id>.json` plus `candidates.json`).
- `docs/classification.md`: verdicts, README sections (`category`), evidence rules and **Maintainer guidance**. Read it before triaging, every time.
- `data/verdicts.json` → `datasets`: one verdict per dataset id, cumulative.

## Steps

1. **Pick searches.** Default is core: ASR, TTS, text generation and translation × trending and downloads, plus `all-name`. A named task or sort ("most downloaded Hebrew ASR datasets") → `--search <id>`; if there's no entry, add one to `hfsearches.json` first (copy an existing one; `task` is the Hub `task_categories` value). `--all` adds the extra categories (classification, NER, QA, summarization, OCR...).
2. **Snapshot.** `uv run scripts/snapshot.py [--search id ...] [--all]`. Commit the snapshot files unedited.
3. **Auto-close tag noise.** Candidates with `hint: no-hebrew-tag` and no prior verdict get `not-relevant` ("no he tag; Hub filter noise") without opening the card, **except** items from the name search or a collection (`seen_in` has `all-name` or `collection:*`), since many Hebrew datasets carry no language tag at all: triage those normally.
4. **Triage the rest** (no `prior_verdict`): `curated` first, then `likely-specialist`, `unclear`, `likely-multilingual`. Read the card when the id and tags don't settle it: `https://huggingface.co/datasets/<id>/raw/main/README.md`. Note size where the card gives it (hours of audio, rows), since that's the first thing a dataset user asks. Write each verdict with `category`, `reason`, `first_seen`, `decided`.
5. **Ask when unsure.** List borderline datasets to the user with your lean; their answer becomes a dated line under Maintainer guidance.
6. **Update the README.** New `specialist` datasets go as cards (house style: `#### Name`, one-line description from the card, a `*Author: x · Size: y · License: z*` details line omitting unknowns, then `[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](url)`) in their section's Hebrew-specific subsection (or directly under the section as `### Name` cards when it has no subsections), alphabetical. New `multilingual-notable` ones go in `### Multilingual datasets with a Hebrew portion` at the end of that section (create it if missing), as cards too, with the Hebrew config/size in the description. Never mix the two. Bump **Last updated**.
7. **Report**: per section, new datasets added (named), auto-closed/skipped counts, open questions.
8. **Commit and push** snapshot, verdicts, README and guidance in one commit.
9. **Offer a Space rebuild** (skill `build-hf-space`) if the README changed.
