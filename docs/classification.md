# Classifying swept datasets: Hebrew-specific or multilingual

A Hugging Face search for Hebrew datasets returns mostly datasets that **include** Hebrew among many
languages (C4, Wikipedia, Common Voice, FLEURS, OPUS...). The list keeps the two apart: each README section
has Hebrew-specific subsections first, then a `### Multilingual datasets with a Hebrew portion` subsection.
Same scheme as the companion repo [Hebrew-AI-Models](https://github.com/danielrosehill/Hebrew-AI-Models).

## Verdicts

Each dataset in `data/verdicts.json` → `datasets` gets exactly one:

| Verdict | Meaning | Goes in README |
|---|---|---|
| `specialist` | Built for Hebrew: Hebrew is the language of the data, or one side of a pair (English-Hebrew code-switching, he↔en parallel text). Includes Hebrew-only subsets and re-packagings of a Hebrew dataset (set `variant_of`). | Hebrew-specific subsections of the section |
| `multilingual-notable` | A multilingual dataset with a usable Hebrew portion worth knowing about: a standard benchmark (FLEURS, Common Voice), a large corpus with a Hebrew config, a parallel corpus with he pairs. Say in the description how to get the Hebrew part (config name, hours, rows) when the card says. | `Multilingual datasets with a Hebrew portion` subsection |
| `multilingual-skip` | Includes Hebrew, nothing Hebrew-specific to say. Recorded so later sweeps skip it. | No |
| `not-relevant` | Carries the Hebrew tag without Hebrew data, empty or broken repos, eval-run dumps, personal test uploads. | No |

Verdict entry shape:

```json
"ivrit-ai/crowd-transcribe-v5": {
  "verdict": "specialist",
  "category": "Audio and Speech",
  "reason": "Crowd-transcribed Hebrew speech from ivrit.ai",
  "variant_of": null,
  "first_seen": "2026-11-18",
  "decided": "2026-11-18"
}
```

## README sections (`category`)

- **Audio and Speech**: ASR corpora, read speech / TTS voices, code-switched speech, audio classification.
- **Sentence Datasets**: sentence banks and prompt sets (for recording, TTS/ASR training, evaluation), sentence pairs.
- **Text Corpora**: pretraining-scale Hebrew text, web/news/religious/legal corpora.
- **Instruction and Chat**: SFT, preference and chat datasets in Hebrew.
- **Translation and Parallel Text**: he↔en and other pairs.
- **NLP Task Datasets**: NER, sentiment, QA, summarization, classification, morphology, nikud.
- **OCR and Handwriting**: printed and handwritten Hebrew text images.
- **Benchmarks and Evaluation**: Hebrew eval sets and leaderboards' data.

## How to tell them apart

1. **Card and configs.** A Hebrew-only dataset, or a `he` config/split that's the whole point → `specialist`. A 100-language dataset where `he` is one config → multilingual.
2. **Language tags.** Five or more `language:` tags and no Hebrew in the name → multilingual. One or two including `he` → read the card.
3. **Name and author.** Hebrew in the id or a known Hebrew org (`known_hebrew_authors` in `hfsearches.json`) → probably specialist; confirm.

`snapshot.py` pre-labels a `hint` from these signals; a hint is not a verdict.

## Maintainer guidance

Rules the maintainer has given for edge cases. Add new ones here, dated, and apply them before the general criteria.

- 2026-11-18: A multilingual dataset that includes Hebrew is not a Hebrew dataset; when it's worth listing it goes in the separate multilingual subsection, never mixed into the Hebrew-specific subsections.
