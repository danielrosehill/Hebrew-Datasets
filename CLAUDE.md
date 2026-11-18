# Hebrew-Datasets

Public catalogue of Hebrew-language datasets (README.md): speech/audio, sentence, text corpora, translation, NLP tasks.
Companion to `danielrosehill/Hebrew-AI-Models` (models); the two share tooling and cross-link.

- Sweeping Hugging Face: repo skill `.claude/skills/hebrew-dataset-sweep/SKILL.md`; follow it for any "update the list" or "sweep" request.
- Saved Hub searches: `hfsearches.json` (`kind: datasets`). Snapshot runner: `uv run scripts/snapshot.py` (stdlib only).
- Dated raw snapshots: `snapshots/YYYY-MM-DD/`, committed unedited.
- Verdicts: `data/verdicts.json` → `datasets`; rules, README sections and maintainer guidance in `docs/classification.md`.
- Curated HF collections: `collections.json`, skill `import-collections`; README cards between `collections:start/end` markers are generated (`scripts/render_collections.py`).
- Hugging Face Space (static, generated from README): `space.json`, `scripts/build_space.py`, skill `build-hf-space`; `space/` is build output.
- `scripts/*.py` are byte-identical with Hebrew-AI-Models; copy changes across.
- Hebrew-specific datasets and multilingual-with-Hebrew datasets never share a subsection; README entries are cards (house style 2026-11-18: alphabetical sections with descriptions, alphabetical cards with badges, no star counts).
