[![Master Index](https://img.shields.io/badge/Master_Index-GitHub-blue?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Start-Here) [![Index of Indexes](https://img.shields.io/badge/Index_of_Indexes-Subindices-FF6B6B?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Subindices)

# Hebrew Datasets

A catalogue of Hebrew-language datasets: speech and audio, sentence datasets, text corpora, instruction data, translation and NLP tasks.

Part of the [Hebrew AI](https://github.com/danielrosehill/Hebrew-AI) index. Models are catalogued in [Hebrew-AI-Models](https://github.com/danielrosehill/Hebrew-AI-Models); people and organisations in [Hebrew-AI-Community](https://github.com/danielrosehill/Hebrew-AI-Community), benchmarks in [Hebrew-AI-Benchmarks](https://github.com/danielrosehill/Hebrew-AI-Benchmarks). Scope: [SCOPE.md](SCOPE.md).

This is a community resource. Contributions welcome via pull request.

**Last updated:** November 18, 2026

---

## Contents

- [Audio and Speech](#audio-and-speech)
- [Instruction and Chat](#instruction-and-chat)
- [NLP Task Datasets](#nlp-task-datasets)
- [OCR and Handwriting](#ocr-and-handwriting)
- [Related](#related)
- [Sentence Datasets](#sentence-datasets)
- [Text Corpora](#text-corpora)
- [Translation and Parallel Text](#translation-and-parallel-text)

---

## Audio and Speech

Hebrew speech corpora, read-speech and TTS voice data, and English-Hebrew code-switched speech.

### Hebrew-Specific Datasets

#### hebrew-speech-dataset

Hebrew speech with transcripts, 16 kHz.

*Author: shunyalabs · Size: 1K – 10K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/shunyalabs/hebrew-speech-dataset)

---

#### Hebrew-talk

Hebrew speech with transcripts (audio and text columns).

*Author: sleeping-ai · Size: 10K – 100K rows · License: mit*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/sleeping-ai/Hebrew-talk)

---

#### hebrew_medical_audio

Hebrew medical-domain audio (gated).

*Author: verbit · Size: 1K – 10K rows · License: cc-by-nc-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/verbit/hebrew_medical_audio)

---

#### hebrew_speech_campus

Hebrew speech from Campus IL video lectures, with subtitles aligned to the audio.

*Author: imvladikon · Size: 10K – 100K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/imvladikon/hebrew_speech_campus)

---

#### hebrew_speech_coursera

Hebrew speech recognition dataset from Coursera course audio.

*Author: imvladikon · Size: 10K – 100K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/imvladikon/hebrew_speech_coursera)

---

#### hebrew_speech_kan

Hebrew speech for ASR (Kan broadcast audio with transcripts).

*Author: imvladikon · Size: 10K – 100K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/imvladikon/hebrew_speech_kan)

---

#### hebrew_speech_kan_nikud

Kan Hebrew speech with vocalised (nikud) transcripts.

*Author: micsell · Size: 10K – 100K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/micsell/hebrew_speech_kan_nikud)

---

#### saspeech

Single-speaker studio Hebrew speech (Shaul Amsterdamski), gold-standard subset of the OpenSLR 134 corpus; for TTS.

*Author: upai-inc · Size: ~4 hours · License: other*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/upai-inc/saspeech)

### Hebrish / danielrosehill

The maintainer's own English-Hebrew code-switching speech datasets, for ASR and TTS.

#### English-Hebrew-Codeswitching-ASR-Benchmark

Benchmark test set for English-Hebrew code-switching ASR.

*Author: Hebrish · Size: <1K rows · License: cc-by-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/Hebrish/English-Hebrew-Codeswitching-ASR-Benchmark)

---

#### English-Hebrew-Codeswitching-Sentences

English-Hebrew code-switching sentences read aloud, for ASR training.

*Author: danielrosehill · Size: 10K – 100K rows · License: cc-by-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/danielrosehill/English-Hebrew-Codeswitching-Sentences)

---

#### English-Hebrew-Mixed-Sentences

"Hebrish": English sentences mixed with Hebrew, audio dataset.

*Author: Hebrish · Size: <1K rows · License: mit*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/Hebrish/English-Hebrew-Mixed-Sentences)

---

#### Hebrish-TTS-Voice-Recordings

English-Hebrew voice recordings for TTS.

*Author: Hebrish · Size: 10K – 100K rows · License: cc-by-nc-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/Hebrish/Hebrish-TTS-Voice-Recordings)

---

#### Hebrish-Validation

Validation benchmark for English-Hebrew code-switching ASR: roughly one-minute reads of a fixed script.

*Author: Hebrish · Size: <1K rows · License: cc-by-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/Hebrish/Hebrish-Validation)

---

#### Israeli-Name-Sentences

Sentences with Israeli names, English-Hebrew code-switching, for ASR.

*Author: Hebrish · Size: <1K rows · License: cc-by-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/Hebrish/Israeli-Name-Sentences)

---

#### Jewish-Religious-Terminology-Sentences

Sentences with Jewish religious terminology, English-Hebrew code-switching, for ASR.

*Author: Hebrish · Size: 1K – 10K rows · License: cc-by-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/Hebrish/Jewish-Religious-Terminology-Sentences)

---

#### Judaica-Sentences

English sentences from traditional Jewish works with Hebrew terms read in; code-switching ASR.

*Author: Hebrish · Size: 1K – 10K rows · License: cc-by-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/Hebrish/Judaica-Sentences)

---

#### Noisy-Condition-Sentences

Code-switching sentences recorded under noisy conditions, for ASR robustness.

*Author: Hebrish · Size: 10K – 100K rows · License: cc-by-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/Hebrish/Noisy-Condition-Sentences)

---

#### Pronunciation-Variants

Takes where a word is deliberately said one particular way (pronunciation variants), for ASR robustness.

*Author: Hebrish · Size: <1K rows · License: cc-by-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/Hebrish/Pronunciation-Variants)

---

#### Read-Aloud-Voice-Sentences

Master set of read-aloud takes from the Hebrish capture app (English with Hebrew code-switching); the split-out datasets are copies of its rows.

*Author: danielrosehill · Size: 10K – 100K rows · License: cc-by-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/danielrosehill/Read-Aloud-Voice-Sentences)

---

#### Small-STT-Eval-Audio-Dataset

Small STT evaluation set: 92 audio samples with ground truth, covering technical vocabulary and English/Hebrew code-switching.

*Author: danielrosehill · Size: 92 samples · License: cc-by-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/danielrosehill/Small-STT-Eval-Audio-Dataset)

### Multilingual datasets with a Hebrew portion

#### fleurs

FLEURS speech benchmark; Hebrew is the `he_il` config.

*Author: google · Size: 100K – 1M rows · License: cc-by-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/google/fleurs)

---

#### yodas

YODAS multilingual YouTube speech; Hebrew is the `iw000` subset.

*Author: espnet · License: cc-by-3.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/espnet/yodas)

---

## Instruction and Chat

Instruction-tuning and chat datasets in Hebrew.

### hebrew_alpaca

Hebrew Alpaca-style instruction data (instruction, input, output).

*Author: ashercn97 · Size: 1K – 10K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/ashercn97/hebrew_alpaca)

---

### Roleplay-Hebrew

Hebrew roleplay instruction data, translated from the GPTeacher roleplay set.

*Author: jojo-ai-mst · Size: 1K – 10K rows · License: mit*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/jojo-ai-mst/Roleplay-Hebrew)

---

## NLP Task Datasets

Labelled Hebrew data for sentiment, paraphrase, metaphor, QA, nikud and other tasks.

### Hebrew-Paraphrase-Dataset

9,785 LLM-generated paraphrase pairs (paragraph and sentence level); 300 manually validated gold.

*Author: HebArabNlpProject · Size: 9,785 instances · License: cc-by-sa-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/HebArabNlpProject/Hebrew-Paraphrase-Dataset)

---

### hebrew_diacritized_text

~5.3M Hebrew sentences with full nikud, from the phonikud knesset_nikud_v6 corpus; for diacritization.

*Author: TigreGotico · Size: ~5.3M sentences · License: cc-by-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/TigreGotico/hebrew_diacritized_text)

---

### hebrew_sentiment

Hebrew sentiment analysis (HebrewSentiment, positive/negative).

*Author: omilab · Size: 10K – 100K rows · License: mit*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/omilab/hebrew_sentiment)

---

### Hebrew_sentiment

Hebrew sentiment classification with binary labels.

*Author: sepidmnorozy · Size: 10K – 100K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/sepidmnorozy/Hebrew_sentiment)

---

### HebrewMetaphors

Hebrew metaphor classification data.

*Author: tdklab · Size: 1K – 10K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/tdklab/HebrewMetaphors)

---

### HebrewSentiment

Hebrew sentiment (positive/negative/neutral) from the Hebrew NLP benchmark collection.

*Author: HebArabNlpProject · Size: 10K – 100K rows · License: other*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/HebArabNlpProject/HebrewSentiment)

---

### wikianswers_hebrew

Hebrew version of WikiAnswers paraphrase/question data.

*Author: imvladikon · Size: 1M – 10M rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/imvladikon/wikianswers_hebrew)

---

## OCR and Handwriting

Images of printed and handwritten Hebrew, with or without transcripts.

### hebrew-handwritten-dataset

HDD_v0: images of isolated handwritten Hebrew characters with train/test split.

*Author: sivan22 · Size: 1K – 10K rows · License: cc-by-3.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/sivan22/hebrew-handwritten-dataset)

---

### Hebrew-Language-Signage

68 photographs of Hebrew signage in Israel (street, commercial and public signs).

*Author: danielrosehill · Size: 68 images*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/danielrosehill/Hebrew-Language-Signage)

---

### hebrew-ocr-dataset

Hebrew text with label and source columns for OCR work.

*Author: mbole · Size: <1K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/mbole/hebrew-ocr-dataset)

---

## Related

Companion lists and other catalogues of Hebrew resources.

### danielrosehill/Hebrew-AI-Models

Companion list: Hebrew LLMs, ASR, TTS, OCR, NLP models.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/danielrosehill/Hebrew-AI-Models)

---

### NNLP-IL/Hebrew-Resources

Comprehensive list of Hebrew NLP resources, including corpora.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/NNLP-IL/Hebrew-Resources)

---

## Sentence Datasets

Hebrew sentence banks and sentence-level corpora.

### hebrew-wikipedia-sentences-corpus

Cleaned, deduplicated Hebrew sentences from 366,610 Hebrew Wikipedia articles (crawled 2026-02).

*Author: tomron87 · Size: 10,999,257 sentences · License: cc-by-sa-3.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/tomron87/hebrew-wikipedia-sentences-corpus)

---

## Text Corpora

Hebrew text for pretraining and domain work: news, Wikipedia, religious and legal texts, lyrics.

### Hebrew-Specific Datasets

#### hebrew-BenIshHai

Halachot from the book Ben Ish Hai, from Hebrew Wikisource.

*Author: AvishayDev · Size: 1K – 10K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/AvishayDev/hebrew-BenIshHai)

---

#### Hebrew-Mil

Hebrew-only PDFs on military and defence topics.

*Author: MetroCat · Size: 1K – 10K rows · License: gpl*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/MetroCat/Hebrew-Mil)

---

#### hebrew_news

Hebrew news articles.

*Author: imvladikon · Size: 100K – 1M rows · License: other*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/imvladikon/hebrew_news)

---

#### Hebrew_Noam30B_Tokenized

Tokenized Hebrew text (input_ids and attention masks) for pretraining.

*Author: simsim314 · License: mit*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/simsim314/Hebrew_Noam30B_Tokenized)

---

#### Hebrew_wikipedia

Most of Hebrew Wikipedia as JSON, crawled breadth-first.

*Author: YanFren · Size: 100K – 1M rows · License: mit*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/YanFren/Hebrew_wikipedia)

---

#### HebrewLyricsDataet

Hebrew song lyrics with title and singer.

*Author: Norod78 · Size: 10K – 100K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/Norod78/HebrewLyricsDataet)

---

#### Judaism-Hebrew

Hebrew Judaism texts (responsa and related).

*Author: guyhadad01 · Size: 1K – 10K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/guyhadad01/Judaism-Hebrew)

---

#### sefaria-hebrew

Jewish texts in Hebrew from the Sefaria project.

*Author: sivan22 · Size: 1M – 10M rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/sivan22/sefaria-hebrew)

---

#### synthetic_hebrew_medical_text

Synthetic Hebrew medical text.

*Author: cp500 · Size: 1K – 10K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/cp500/synthetic_hebrew_medical_text)

---

#### Talmud-Hebrew

Talmud Bavli text in Hebrew from Wikisource.

*Author: guyhadad01 · Size: <1K rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/guyhadad01/Talmud-Hebrew)

### Multilingual datasets with a Hebrew portion

#### fine-news

Multilingual news corpus from Common Crawl News; Hebrew is the `heb_Hebr` partition.

*Author: ksolovev · Size: 100M – 1B rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/ksolovev/fine-news)

---

#### wikipedia

Wikipedia dumps; Hebrew is the `20231101.he` config.

*Author: wikimedia · Size: 10M – 100M rows · License: cc-by-sa-3.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/wikimedia/wikipedia)

---

## Translation and Parallel Text

Parallel text pairing Hebrew with other languages.

### Multilingual datasets with a Hebrew portion

#### flores_plus

FLORES+ translation benchmark; Hebrew is `heb_Hebr` (also Yiddish `ydd_Hebr`).

*Author: openlanguagedata · Size: 100K – 1M rows · License: cc-by-sa-4.0*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/openlanguagedata/flores_plus)

---

#### parallel-sentences-global-voices

Global Voices news pairs; Hebrew is the `en-he` subset.

*Author: sentence-transformers · Size: 1M – 10M rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/sentence-transformers/parallel-sentences-global-voices)

---

#### parallel-sentences-talks

TED-style talk pairs; Hebrew is the `en-he` subset.

*Author: sentence-transformers · Size: 10M – 100M rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/sentence-transformers/parallel-sentences-talks)

---

#### parallel-sentences-tatoeba

Tatoeba sentence pairs; Hebrew is the `en-he` subset.

*Author: sentence-transformers · Size: 1M – 10M rows*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/sentence-transformers/parallel-sentences-tatoeba)

---

## Curated HF Collections

Curated Hugging Face collections (by danielrosehill) that feed this list:

<!-- collections:start -->
<!-- Generated from collections.json by scripts/render_collections.py; edit that file, not these cards. -->

### Audio Datasets - Mine

The maintainer's own audio datasets.

[![Collection](https://img.shields.io/badge/Hugging_Face-Collection-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/collections/danielrosehill/audio-datasets-mine-6aee9e80cb04e786c3fdbeaa)

---

### Audio Datasets - Third Party Classics

Well-known third-party audio datasets.

[![Collection](https://img.shields.io/badge/Hugging_Face-Collection-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/collections/danielrosehill/audio-datasets-third-party-classics-6aeea2c2b9ec48969f48e054)

---

### Code Switching (English And Hebrew) - All Resources

English-Hebrew code-switching models and datasets.

[![Collection](https://img.shields.io/badge/Hugging_Face-Collection-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/collections/danielrosehill/code-switching-english-and-hebrew-all-resources-6acfdcb1e11911797af4c3b3)

---

### Hebrew

General Hebrew collection: models and datasets across tasks.

[![Collection](https://img.shields.io/badge/Hugging_Face-Collection-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/collections/danielrosehill/hebrew-6ad68f42575d0b5073d19e86)

---

### Hebrew audio datasets

Hebrew speech and audio datasets.

[![Collection](https://img.shields.io/badge/Hugging_Face-Collection-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/collections/danielrosehill/hebrew-audio-datasets-6ad6923f2ea298b0df13adf5)

---

### Hebrew datasets

Hebrew text and NLP datasets.

[![Collection](https://img.shields.io/badge/Hugging_Face-Collection-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/collections/danielrosehill/hebrew-datasets-680428e2813deb0a8b8d1271)

---

### Israel Context Datasets

Datasets about Israel, often Hebrew-language.

[![Collection](https://img.shields.io/badge/Hugging_Face-Collection-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/collections/danielrosehill/israel-context-datasets-6ad676a3773a64192165a96c)

---

### Israel Open Data

Israeli government open data on the Hub.

[![Collection](https://img.shields.io/badge/Hugging_Face-Collection-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/collections/danielrosehill/israel-open-data-69fba702e180798fe3761073)

---

### Sentence Datasets - All

Sentence datasets (mixed languages; Hebrew ones are listed here).

[![Collection](https://img.shields.io/badge/Hugging_Face-Collection-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/collections/danielrosehill/sentence-datasets-all-6aeeb0facb33a09378459623)

---

### Sentence Datasets - Mine

The maintainer's own sentence datasets.

[![Collection](https://img.shields.io/badge/Hugging_Face-Collection-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/collections/danielrosehill/sentence-datasets-mine-6aeeb2ae61663e960fade58c)

---

### Sentence Datasets - Third Party

Third-party sentence datasets.

[![Collection](https://img.shields.io/badge/Hugging_Face-Collection-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/collections/danielrosehill/sentence-datasets-third-party-6aeea2c7b5a404455057151a)

---

All collections: [https://huggingface.co/danielrosehill/collections](https://huggingface.co/danielrosehill/collections)
<!-- collections:end -->

---

## How this list is maintained

Datasets are swept from Hugging Face with saved searches ([`hfsearches.json`](hfsearches.json)): the Hebrew language tag plus a task category (speech recognition, text-to-speech, text generation, translation and others), sorted by trending or downloads, plus a name search for "heb". The maintainer's curated collections ([`collections.json`](collections.json)) are imported the same way. Each run keeps a dated raw snapshot in [`snapshots/`](snapshots/) and every dataset gets a recorded verdict in [`data/verdicts.json`](data/verdicts.json).

Most datasets tagged Hebrew on the Hub are multilingual datasets with a Hebrew portion. This list keeps them apart: **Hebrew-specific** datasets fill the main sections, and notable multilingual datasets go in a separate *Multilingual datasets with a Hebrew portion* subsection. Criteria: [`docs/classification.md`](docs/classification.md).

## Contributing

Maintained on a best-effort basis by [Daniel Rosehill](https://github.com/danielrosehill). To be included, or to send a correction, open a pull request or email public@danielrosehill.com.

## License

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a Creative Commons Attribution 4.0 International License.
