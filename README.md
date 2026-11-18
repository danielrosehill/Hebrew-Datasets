[![Master Index](https://img.shields.io/badge/Master_Index-GitHub-blue?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Start-Here)

# Hebrew Datasets

A catalogue of Hebrew-language datasets: speech and audio, sentence datasets, text corpora, instruction data, translation and NLP tasks.

Part of the [Hebrew AI](https://github.com/danielrosehill/Hebrew-AI) index. Models are catalogued in [Hebrew-AI-Models](https://github.com/danielrosehill/Hebrew-AI-Models); people and organisations in [Hebrew-AI-Community](https://github.com/danielrosehill/Hebrew-AI-Community), benchmarks in [Hebrew-AI-Benchmarks](https://github.com/danielrosehill/Hebrew-AI-Benchmarks). Scope: [SCOPE.md](SCOPE.md).

This is a community resource. Contributions welcome via pull request.

**Last updated:** November 18, 2026

---

## Audio and Speech

| Dataset | Author | Size | License | Description |
|---|---|---|---|---|
| [hebrew_speech_kan](https://huggingface.co/datasets/imvladikon/hebrew_speech_kan) | imvladikon | 10K – 100K rows | — | Hebrew speech for ASR (Kan broadcast audio with transcripts). |
| [hebrew_speech_coursera](https://huggingface.co/datasets/imvladikon/hebrew_speech_coursera) | imvladikon | 10K – 100K rows | — | Hebrew speech recognition dataset from Coursera course audio. |
| [hebrew_speech_campus](https://huggingface.co/datasets/imvladikon/hebrew_speech_campus) | imvladikon | 10K – 100K rows | — | Hebrew speech from Campus IL video lectures, with subtitles aligned to the audio. |
| [saspeech](https://huggingface.co/datasets/upai-inc/saspeech) | upai-inc | ~4 hours | other | Single-speaker studio Hebrew speech (Shaul Amsterdamski), gold-standard subset of the OpenSLR 134 corpus; for TTS. |
| [Hebrew-talk](https://huggingface.co/datasets/sleeping-ai/Hebrew-talk) | sleeping-ai | 10K – 100K rows | mit | Hebrew speech with transcripts (audio and text columns). |
| [hebrew-speech-dataset](https://huggingface.co/datasets/shunyalabs/hebrew-speech-dataset) | shunyalabs | 1K – 10K rows | — | Hebrew speech with transcripts, 16 kHz. |
| [hebrew_speech_kan_nikud](https://huggingface.co/datasets/micsell/hebrew_speech_kan_nikud) | micsell | 10K – 100K rows | — | Kan Hebrew speech with vocalised (nikud) transcripts. |
| [hebrew_medical_audio](https://huggingface.co/datasets/verbit/hebrew_medical_audio) | verbit | 1K – 10K rows | cc-by-nc-4.0 | Hebrew medical-domain audio (gated). |

### Hebrish / danielrosehill

The maintainer's own English-Hebrew code-switching speech datasets, for ASR and TTS.

| Dataset | Author | Size | License | Description |
|---|---|---|---|---|
| [English-Hebrew-Codeswitching-Sentences](https://huggingface.co/datasets/danielrosehill/English-Hebrew-Codeswitching-Sentences) | danielrosehill | 10K – 100K rows | cc-by-4.0 | English-Hebrew code-switching sentences read aloud, for ASR training. |
| [Noisy-Condition-Sentences](https://huggingface.co/datasets/Hebrish/Noisy-Condition-Sentences) | Hebrish | 10K – 100K rows | cc-by-4.0 | Code-switching sentences recorded under noisy conditions, for ASR robustness. |
| [Hebrish-TTS-Voice-Recordings](https://huggingface.co/datasets/Hebrish/Hebrish-TTS-Voice-Recordings) | Hebrish | 10K – 100K rows | cc-by-nc-4.0 | English-Hebrew voice recordings for TTS. |
| [Jewish-Religious-Terminology-Sentences](https://huggingface.co/datasets/Hebrish/Jewish-Religious-Terminology-Sentences) | Hebrish | 1K – 10K rows | cc-by-4.0 | Sentences with Jewish religious terminology, English-Hebrew code-switching, for ASR. |
| [Israeli-Name-Sentences](https://huggingface.co/datasets/Hebrish/Israeli-Name-Sentences) | Hebrish | <1K rows | cc-by-4.0 | Sentences with Israeli names, English-Hebrew code-switching, for ASR. |
| [Pronunciation-Variants](https://huggingface.co/datasets/Hebrish/Pronunciation-Variants) | Hebrish | <1K rows | cc-by-4.0 | Takes where a word is deliberately said one particular way (pronunciation variants), for ASR robustness. |
| [Hebrish-Validation](https://huggingface.co/datasets/Hebrish/Hebrish-Validation) | Hebrish | <1K rows | cc-by-4.0 | Validation benchmark for English-Hebrew code-switching ASR: roughly one-minute reads of a fixed script. |
| [English-Hebrew-Codeswitching-ASR-Benchmark](https://huggingface.co/datasets/Hebrish/English-Hebrew-Codeswitching-ASR-Benchmark) | Hebrish | <1K rows | cc-by-4.0 | Benchmark test set for English-Hebrew code-switching ASR. |
| [English-Hebrew-Mixed-Sentences](https://huggingface.co/datasets/Hebrish/English-Hebrew-Mixed-Sentences) | Hebrish | <1K rows | mit | "Hebrish": English sentences mixed with Hebrew, audio dataset. |
| [Read-Aloud-Voice-Sentences](https://huggingface.co/datasets/danielrosehill/Read-Aloud-Voice-Sentences) | danielrosehill | 10K – 100K rows | cc-by-4.0 | Master set of read-aloud takes from the Hebrish capture app (English with Hebrew code-switching); the split-out datasets are copies of its rows. |
| [Small-STT-Eval-Audio-Dataset](https://huggingface.co/datasets/danielrosehill/Small-STT-Eval-Audio-Dataset) | danielrosehill | 92 samples | cc-by-4.0 | Small STT evaluation set: 92 audio samples with ground truth, covering technical vocabulary and English/Hebrew code-switching. |
| [Judaica-Sentences](https://huggingface.co/datasets/Hebrish/Judaica-Sentences) | Hebrish | 1K – 10K rows | cc-by-4.0 | English sentences from traditional Jewish works with Hebrew terms read in; code-switching ASR. |

### Multilingual datasets with a Hebrew portion

| Dataset | Author | Size | License | Description |
|---|---|---|---|---|
| [fleurs](https://huggingface.co/datasets/google/fleurs) | google | 100K – 1M rows | cc-by-4.0 | FLEURS speech benchmark; Hebrew is the `he_il` config. |
| [yodas](https://huggingface.co/datasets/espnet/yodas) | espnet | — | cc-by-3.0 | YODAS multilingual YouTube speech; Hebrew is the `iw000` subset. |

## Sentence Datasets

| Dataset | Author | Size | License | Description |
|---|---|---|---|---|
| [hebrew-wikipedia-sentences-corpus](https://huggingface.co/datasets/tomron87/hebrew-wikipedia-sentences-corpus) | tomron87 | 10,999,257 sentences | cc-by-sa-3.0 | Cleaned, deduplicated Hebrew sentences from 366,610 Hebrew Wikipedia articles (crawled 2026-02). |

## Text Corpora

| Dataset | Author | Size | License | Description |
|---|---|---|---|---|
| [Hebrew_Noam30B_Tokenized](https://huggingface.co/datasets/simsim314/Hebrew_Noam30B_Tokenized) | simsim314 | — | mit | Tokenized Hebrew text (input_ids and attention masks) for pretraining. |
| [sefaria-hebrew](https://huggingface.co/datasets/sivan22/sefaria-hebrew) | sivan22 | 1M – 10M rows | — | Jewish texts in Hebrew from the Sefaria project. |
| [hebrew_news](https://huggingface.co/datasets/imvladikon/hebrew_news) | imvladikon | 100K – 1M rows | other | Hebrew news articles. |
| [hebrew-BenIshHai](https://huggingface.co/datasets/AvishayDev/hebrew-BenIshHai) | AvishayDev | 1K – 10K rows | — | Halachot from the book Ben Ish Hai, from Hebrew Wikisource. |
| [HebrewLyricsDataet](https://huggingface.co/datasets/Norod78/HebrewLyricsDataet) | Norod78 | 10K – 100K rows | — | Hebrew song lyrics with title and singer. |
| [Judaism-Hebrew](https://huggingface.co/datasets/guyhadad01/Judaism-Hebrew) | guyhadad01 | 1K – 10K rows | — | Hebrew Judaism texts (responsa and related). |
| [Talmud-Hebrew](https://huggingface.co/datasets/guyhadad01/Talmud-Hebrew) | guyhadad01 | <1K rows | — | Talmud Bavli text in Hebrew from Wikisource. |
| [Hebrew_wikipedia](https://huggingface.co/datasets/YanFren/Hebrew_wikipedia) | YanFren | 100K – 1M rows | mit | Most of Hebrew Wikipedia as JSON, crawled breadth-first. |
| [synthetic_hebrew_medical_text](https://huggingface.co/datasets/cp500/synthetic_hebrew_medical_text) | cp500 | 1K – 10K rows | — | Synthetic Hebrew medical text. |
| [Hebrew-Mil](https://huggingface.co/datasets/MetroCat/Hebrew-Mil) | MetroCat | 1K – 10K rows | gpl | Hebrew-only PDFs on military and defence topics. |

### Multilingual datasets with a Hebrew portion

| Dataset | Author | Size | License | Description |
|---|---|---|---|---|
| [wikipedia](https://huggingface.co/datasets/wikimedia/wikipedia) | wikimedia | 10M – 100M rows | cc-by-sa-3.0 | Wikipedia dumps; Hebrew is the `20231101.he` config. |
| [fine-news](https://huggingface.co/datasets/ksolovev/fine-news) | ksolovev | 100M – 1B rows | — | Multilingual news corpus from Common Crawl News; Hebrew is the `heb_Hebr` partition. |

## Instruction and Chat

| Dataset | Author | Size | License | Description |
|---|---|---|---|---|
| [hebrew_alpaca](https://huggingface.co/datasets/ashercn97/hebrew_alpaca) | ashercn97 | 1K – 10K rows | — | Hebrew Alpaca-style instruction data (instruction, input, output). |
| [Roleplay-Hebrew](https://huggingface.co/datasets/jojo-ai-mst/Roleplay-Hebrew) | jojo-ai-mst | 1K – 10K rows | mit | Hebrew roleplay instruction data, translated from the GPTeacher roleplay set. |

## Translation and Parallel Text

### Multilingual datasets with a Hebrew portion

| Dataset | Author | Size | License | Description |
|---|---|---|---|---|
| [flores_plus](https://huggingface.co/datasets/openlanguagedata/flores_plus) | openlanguagedata | 100K – 1M rows | cc-by-sa-4.0 | FLORES+ translation benchmark; Hebrew is `heb_Hebr` (also Yiddish `ydd_Hebr`). |
| [parallel-sentences-tatoeba](https://huggingface.co/datasets/sentence-transformers/parallel-sentences-tatoeba) | sentence-transformers | 1M – 10M rows | — | Tatoeba sentence pairs; Hebrew is the `en-he` subset. |
| [parallel-sentences-talks](https://huggingface.co/datasets/sentence-transformers/parallel-sentences-talks) | sentence-transformers | 10M – 100M rows | — | TED-style talk pairs; Hebrew is the `en-he` subset. |
| [parallel-sentences-global-voices](https://huggingface.co/datasets/sentence-transformers/parallel-sentences-global-voices) | sentence-transformers | 1M – 10M rows | — | Global Voices news pairs; Hebrew is the `en-he` subset. |

## NLP Task Datasets

| Dataset | Author | Size | License | Description |
|---|---|---|---|---|
| [hebrew_sentiment](https://huggingface.co/datasets/omilab/hebrew_sentiment) | omilab | 10K – 100K rows | mit | Hebrew sentiment analysis (HebrewSentiment, positive/negative). |
| [HebrewSentiment](https://huggingface.co/datasets/HebArabNlpProject/HebrewSentiment) | HebArabNlpProject | 10K – 100K rows | other | Hebrew sentiment (positive/negative/neutral) from the Hebrew NLP benchmark collection. |
| [Hebrew_sentiment](https://huggingface.co/datasets/sepidmnorozy/Hebrew_sentiment) | sepidmnorozy | 10K – 100K rows | — | Hebrew sentiment classification with binary labels. |
| [HebrewMetaphors](https://huggingface.co/datasets/tdklab/HebrewMetaphors) | tdklab | 1K – 10K rows | — | Hebrew metaphor classification data. |
| [Hebrew-Paraphrase-Dataset](https://huggingface.co/datasets/HebArabNlpProject/Hebrew-Paraphrase-Dataset) | HebArabNlpProject | 9,785 instances | cc-by-sa-4.0 | 9,785 LLM-generated paraphrase pairs (paragraph and sentence level); 300 manually validated gold. |
| [wikianswers_hebrew](https://huggingface.co/datasets/imvladikon/wikianswers_hebrew) | imvladikon | 1M – 10M rows | — | Hebrew version of WikiAnswers paraphrase/question data. |
| [hebrew_diacritized_text](https://huggingface.co/datasets/TigreGotico/hebrew_diacritized_text) | TigreGotico | ~5.3M sentences | cc-by-4.0 | ~5.3M Hebrew sentences with full nikud, from the phonikud knesset_nikud_v6 corpus; for diacritization. |

## OCR and Handwriting

| Dataset | Author | Size | License | Description |
|---|---|---|---|---|
| [hebrew-handwritten-dataset](https://huggingface.co/datasets/sivan22/hebrew-handwritten-dataset) | sivan22 | 1K – 10K rows | cc-by-3.0 | HDD_v0: images of isolated handwritten Hebrew characters with train/test split. |
| [hebrew-ocr-dataset](https://huggingface.co/datasets/mbole/hebrew-ocr-dataset) | mbole | <1K rows | — | Hebrew text with label and source columns for OCR work. |
| [Hebrew-Language-Signage](https://huggingface.co/datasets/danielrosehill/Hebrew-Language-Signage) | danielrosehill | 68 images | — | 68 photographs of Hebrew signage in Israel (street, commercial and public signs). |

---

## Curated HF Collections

Curated Hugging Face collections (by danielrosehill) that feed this list:

<!-- collections:start -->
<!-- Generated from collections.json by scripts/render_collections.py; edit that file, not this table. -->
| Collection | Contents |
|------------|----------|
| [Hebrew audio datasets](https://huggingface.co/collections/danielrosehill/hebrew-audio-datasets-6ad6923f2ea298b0df13adf5) | Hebrew speech and audio datasets |
| [Hebrew datasets](https://huggingface.co/collections/danielrosehill/hebrew-datasets-680428e2813deb0a8b8d1271) | Hebrew text and NLP datasets |
| [Hebrew](https://huggingface.co/collections/danielrosehill/hebrew-6ad68f42575d0b5073d19e86) | General Hebrew collection: models and datasets across tasks |
| [Code Switching (English And Hebrew) - All Resources](https://huggingface.co/collections/danielrosehill/code-switching-english-and-hebrew-all-resources-6acfdcb1e11911797af4c3b3) | English-Hebrew code-switching models and datasets |
| [Sentence Datasets - All](https://huggingface.co/collections/danielrosehill/sentence-datasets-all-6aeeb0facb33a09378459623) | Sentence datasets (mixed languages; Hebrew ones are listed here) |
| [Sentence Datasets - Mine](https://huggingface.co/collections/danielrosehill/sentence-datasets-mine-6aeeb2ae61663e960fade58c) | The maintainer's own sentence datasets |
| [Sentence Datasets - Third Party](https://huggingface.co/collections/danielrosehill/sentence-datasets-third-party-6aeea2c7b5a404455057151a) | Third-party sentence datasets |
| [Audio Datasets - Mine](https://huggingface.co/collections/danielrosehill/audio-datasets-mine-6aee9e80cb04e786c3fdbeaa) | The maintainer's own audio datasets |
| [Audio Datasets - Third Party Classics](https://huggingface.co/collections/danielrosehill/audio-datasets-third-party-classics-6aeea2c2b9ec48969f48e054) | Well-known third-party audio datasets |
| [Israel Context Datasets](https://huggingface.co/collections/danielrosehill/israel-context-datasets-6ad676a3773a64192165a96c) | Datasets about Israel, often Hebrew-language |
| [Israel Open Data](https://huggingface.co/collections/danielrosehill/israel-open-data-69fba702e180798fe3761073) | Israeli government open data on the Hub |

All collections: [https://huggingface.co/danielrosehill/collections](https://huggingface.co/danielrosehill/collections)
<!-- collections:end -->

---

## Related

| Resource | Description |
|----------|-------------|
| [danielrosehill/Hebrew-AI-Models](https://github.com/danielrosehill/Hebrew-AI-Models) | Companion list: Hebrew LLMs, ASR, TTS, OCR, NLP models |
| [NNLP-IL/Hebrew-Resources](https://github.com/NNLP-IL/Hebrew-Resources) | Comprehensive list of Hebrew NLP resources, including corpora |

---

## How this list is maintained

Datasets are swept from Hugging Face with saved searches ([`hfsearches.json`](hfsearches.json)): the Hebrew language tag plus a task category (speech recognition, text-to-speech, text generation, translation and others), sorted by trending or downloads, plus a name search for "heb". The maintainer's curated collections ([`collections.json`](collections.json)) are imported the same way. Each run keeps a dated raw snapshot in [`snapshots/`](snapshots/) and every dataset gets a recorded verdict in [`data/verdicts.json`](data/verdicts.json).

Most datasets tagged Hebrew on the Hub are multilingual datasets with a Hebrew portion. This list keeps them apart: **Hebrew-specific** datasets fill the main tables, and notable multilingual datasets go in a separate *Multilingual datasets with a Hebrew portion* subsection. Criteria: [`docs/classification.md`](docs/classification.md).

## Contributing

Maintained on a best-effort basis by [Daniel Rosehill](https://github.com/danielrosehill). To be included, or to send a correction, open a pull request or email public@danielrosehill.com.

## License

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a Creative Commons Attribution 4.0 International License.
