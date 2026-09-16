---
layout: post
title: Brazilian Portuguese Speech Datasets
date: 2026-05-17 12:00:00 -0300
image: aitmp.png
image_bg: speech_bg.jpeg
type: speech
tags: [speech, dataset]
demo: https://www.youtube.com/watch?v=W_EPr3_cpdc&list=RDW_EPr3_cpdc&start_radio=1
---

> **📅 Last Updated: September 16, 2026**  
> *Added YODAS-Granary (13.4k hours) and the CoLingPB sociolinguistic corpus to the ASR resources.*

Here is a comprehensive compilation of speech datasets available for Brazilian Portuguese (pt-BR) categorized by task and ordered chronologically.

---

## Automatic Speech Recognition (ASR)

---
---

### Multilingual LibriSpeech (MLS) — pt-BR (2020)
**Multi-speaker · Large-scale · Read audiobook · 8 languages**

Large multilingual corpus derived from LibriVox audiobooks across 8 languages. The Portuguese partition offers hundreds of hours of read audiobook speech, making it one of the largest publicly available pt-BR ASR datasets.

- **Authors:** Vineel Pratap, Qiantong Xu, Anuroop Sriram, Gabriel Synnaeve, Ronan Collobert
- **Download:** [OpenSLR Repository](https://www.openslr.org/94/)
- **Paper:** [ISCA Archive](https://www.isca-archive.org/interspeech_2020/pratap20_interspeech.pdf)

---

### Sidney & VoxForge (2020)
**72 / 111+ speakers · Non-controlled · Diverse tasks · Word-level transcription**

Two corpora available from a unified page.

**Sidney:** 72 speakers (20 women, ages 17–59), 5,777 utterances covering digits, words, phonetic sentences and more, recorded at 22 kHz in non-controlled environments. Fields include place of birth, age, gender, education, and occupation.

**VoxForge:** Crowd-sourced GPL corpus with 111+ speakers, 4,130 pt-BR utterances at varying sample rates (16–44.1 kHz); highly heterogeneous quality with low SNR on many recordings.

- **Authors:** No paper related
- **Download:** [Datasets Page](https://igormq.github.io/datasets/) *(contains individual download links for both corpora)*

---

### mTEDx (2021)
**Multi-speaker · Semi-spontaneous · 8 languages · Sentence-aligned**

Sentence-level aligned TEDx Talk recordings and transcripts in 8 languages including pt-BR, with translations into up to 5 languages. Covers natural, semi-spontaneous public speaking across diverse topics.

- **Authors:** Elizabeth Salesky, Matthew Wiesner, Jacob Bremerman, Roldano Cattoni, Matteo Negri, Marco Turchi, Douglas W. Oard, Matt Post
- **Download:** [OpenSLR Repository](https://www.openslr.org/100)
- **Paper:** [ISCA Archive](https://www.isca-archive.org/interspeech_2021/salesky21_interspeech.pdf)

---

### CORAA v1.1 (2021)
**Multi-speaker · ~291 h · 400k+ clips · Varied sources**

Large publicly available pt-BR ASR dataset with 290.77 hours of audio and 400k+ segmented transcribed utterances. Covers a broad range of sources and speaking styles.

- **Authors:** Arnaldo Candido Junior, Edresson Casanova, Anderson Soares, Frederico Santos de Oliveira, Lucas Oliveira, Ricardo Corso Fernandes Junior, Daniel Peixoto Pinto da Silva, Fernando Gorgulho Fayet, Bruno Baldissera Carlotto, Lucas Rafael Stefanel Gris, Sandra Maria Aluísio
- **Download:** [Hugging Face](https://huggingface.co/datasets/gabrielrstan/CORAA-v1.1)
- **Paper:** [Springer](https://link.springer.com/article/10.1007/s10579-022-09621-4)

---

### CORAA NURC-SP (2024)
**Multi-speaker · ~240 h · 170k+ clips · Naturalistic · São Paulo dialect**

Pt-BR ASR corpus with 239.68 hours (239.30 h filtered) and 170k+ segmented utterances, derived from the NURC-SP sociolinguistic corpus of São Paulo speech. Covers naturalistic spoken language with diverse sociolinguistic profiles.

- **Authors:** Rodrigo Lima, Sidney E. Leal, Arnaldo Candido Junior, Sandra M. Aluísio
- **Download:** [Hugging Face](https://huggingface.co/datasets/nilc-nlp/CORAA-NURC-SP-Audio-Corpus)
- **Paper:** [SBC Open Lib](https://sol.sbc.org.br/index.php/bracis/article/view/33550)

---

### CORAA MUPE ASR (2025)
**289 speakers · 365 h · Spontaneous interviews · Regional diversity**

Life story interview corpus with 289 interviews totalling 365 hours. Highly diverse in age, education, and regional accent — well-suited for robustness testing across sociolinguistic variation.

- **Authors:** Sidney Evaldo Leal, Arnaldo Candido Junior, Ricardo Marcacini, Edresson Casanova, Odilon Gonçalves, Anderson Silva Soares, Rodrigo Freitas Lima, Lucas Rafael Stefanel Gris, Sandra Aluísio
- **Download:** [Hugging Face](https://huggingface.co/datasets/nilc-nlp/CORAA-MUPE-ASR)
- **Paper:** [ACL Anthology](https://aclanthology.org/2025.coling-main.407/)

---

### TAGARELA (2026)
**Multi-speaker · 8,972+ h total · ~2k h TTS subset · Podcast / spontaneous · ASR + TTS**

Massive podcast-derived corpus with 8,972+ hours of naturalistic conversational pt-BR. Includes a high-quality ~2k-hour subset curated for TTS. One of the largest open pt-BR speech resources available.

- **Authors:** Frederico Santos De Oliveira, Lucas Rafael Stefanel Gris, Alef Iury Siqueira Ferreira, Augusto Seben Da Rosa, Alexandre Costa Ferro Filho, Edresson Casanova
- **Download:** [Hugging Face](https://huggingface.co/datasets/freds0/TAGARELA)
- **Paper:** [IEEE Xplore](https://ieeexplore.ieee.org/document/11462137)

---

### CoLingPB — Corpus Linguístico da Paraíba (2015)
**Unknown size · Raw conversational audio · Multi-turn annotations · Paraíba dialect**

A sociolinguistic documentary corpus aimed at preserving the dialectal varieties of the Brazilian state of Paraíba. Recorded between 2011 and 2014, the dataset provides raw audio interviews accompanied by text transcriptions and multi-turn conversational markers. Because the audio files and transcriptions are distributed separately across individual project publications rather than a centralized repository, consolidating the full corpus requires web scraping. The total duration and exact number of utterances are unspecified.

- **Authors:** Cirineu Cecote Stein (coordinator), Anna Elizabeth de C. C. da Silveira, Elioenai Macena de Araújo, Felipe de Castro Cruz, Lucas Hudson Pequeno da Silva, Maria Cristina da Silva Lima, Solange Soares Costa
- **Download:** Distributed across multiple publications (requires web scraping to consolidate)
- **Source:** Funded by MEC/SESu (PROEXT) and executed at UFPB (2011–2015)

---

### YODAS-Granary (2025)
**Multi-speaker · 13.4k h (pt) · Pseudo-labeled · ASR + AST**

A curated subset of the larger nvidia/Granary dataset, derived from the espnet/yodas2 corpus. The Portuguese partition contains approximately 13.4k hours of speech. Although officially categorized under European Portuguese in the metadata, the vast majority of the audio features Brazilian Portuguese. It provides high-quality pseudo-labeled data for both Automatic Speech Recognition (ASR) and Automatic Speech Translation (AST). ASR transcriptions were generated using Systran/faster-whisper-large-v3 and refined for punctuation/capitalization with Qwen/Qwen2.5-7B-Instruct, while AST translations to English were generated using utter-project/EuroLLM-9B-Instruct.

- **Authors:** Nithin Rao Koluguri, Monica Sekoyan, George Zelenfroynd, Sasha Meister, Shuoyang Ding, Sofia Kostandian, He Huang, Nikolay Karpov, Jagadeesh Balam, Vitaly Lavrukhin, Yifan Peng, Sara Papi, Marco Gaido, Alessio Brutti, Boris Ginsburg
- **Download:** [Hugging Face](https://huggingface.co/datasets/espnet/yodas-granary)
- **Paper:** [arXiv:2505.13404](https://arxiv.org/abs/2505.13404)

---

## Text-to-Speech (TTS)

---
---

### TTS Portuguese Corpus (2020)
**Single speaker · ~10.5 h · Read speech · 48 kHz**

Single-speaker corpus with ~10.5 hours of clean studio-quality speech (48 kHz), comprising 3,632 Wave files ranging from 0.7 to 50 seconds. Designed for TTS but widely used for ASR benchmarking.

- **Authors:** Edresson Casanova, Arnaldo Candido Junior, Christopher Shulby, Frederico Santos de Oliveira, João Paulo Teixeira, Moacir Antonelli Ponti, Sandra Maria Aluisio
- **Download:** [GitHub Repository](https://github.com/Edresson/TTS-Portuguese-Corpus)
- **Paper:** [Springer](https://link.springer.com/article/10.1007/s10579-021-09570-4)

---

### Globo Speech Datasets (2023)
**Single speaker each · ~20 h each · Studio quality**

High-quality studio-grade speech corpora from Globo, each ~20 hours. Comparable to LJSpeech in quality. Two releases: a female speaker corpus and a general (male) speaker corpus.

- **Authors:** Pedro H. L. Leite, Edmundo Hoyle, Álvaro Antelo, Luiz F. Kruszielski, Luiz W. P. Biscainho 
- **Download (Female):** [Kaggle — g-neutral-speech-female](https://www.kaggle.com/datasets/mediatechlab/g-neutral-speech-female)
- **Paper:** [SBrT 2023](https://biblioteca.sbrt.org.br/articles/4464)
- **Download (Male):** [Kaggle — gneutralspeech](https://www.kaggle.com/datasets/mediatechlab/gneutralspeech)
- **Paper:** [PROPOR 2022](https://link.springer.com/chapter/10.1007/978-3-030-98305-5_32)

---

### CML-TTS (2023)
**Multi-speaker · Read audiobook · 7 languages · TTS-optimized**

Derived from MLS and adapted for TTS training across 7 languages including pt-BR. Provides cleaner segmentation and metadata more suitable for speech synthesis than the original MLS splits.

- **Authors:** Oliveira, Frederico S. and Casanova, Edresson and Junior, Arnaldo Candido and Soares, Anderson S. and Galvão Filho, Arlindo R.
- **Download:** [GitHub Repository](https://github.com/freds0/CML-TTS-Dataset)
- **Paper:** [ACM DL](https://dl.acm.org/doi/10.1007/978-3-031-40498-6_17)

---

### CommonVoice Consolidated (pt-BR) (2025)
**Multi-speaker · Crowd-sourced · TTS-optimized**

Preprocessed and merged version of Mozilla Common Voice pt-BR, with filtered, normalized audio clips optimized for both ASR and TTS training pipelines.

- **Authors:** No paper related
- **Download:** [Hugging Face](https://huggingface.co/datasets/firstpixel/pt-br_char)

---

### FalaBrasil Consolidado (2025)
**Multi-speaker · Varied sources · TTS-optimized**

Consolidated multi-speaker pt-BR speech corpus assembled from the FalaBrasil fb-audio-corpora GitLab repository, covering a range of speaking conditions suitable for TTS training.

- **Authors:** No paper related
- **Download:** [Hugging Face](https://huggingface.co/datasets/Tharyck/multispeaker-tts-ptbr)
- **Source:** [GitLab Repository](https://gitlab.com/fb-audio-corpora)

---

### NURC ENTOA TTS (2025)
**Multi-speaker · TTS-optimized · 4 configurations · São Paulo dialect**

TTS-focused corpus derived from the NURC-SP project with 4 configurations: prosodic, automatic, audioCorpus, and test. Captures naturalistic São Paulo speech adapted for synthesis tasks.

- **Authors:** No paper related
- **Download:** [Hugging Face](https://huggingface.co/datasets/nilc-nlp/NURC-SP_ENTOA_TTS)

---

### NURC TTS (2026)
**Multi-speaker · TTS-optimized · São Paulo + Recife dialects**

Two-partition corpus covering São Paulo and Recife dialects. Overlaps with NURC-SP and CORAA datasets. Useful for multi-dialect TTS coverage across Brazilian Portuguese regional varieties.

- **Authors:** No paper related
- **Download:** [Hugging Face](https://huggingface.co/datasets/nilc-nlp/nurc_tts)

---

## Speech Emotion Recognition (SER)

---
---

### VERBO (2018)
**Acted · 6 emotions (Ekman) · 12 actors · 1,167 sentences · Discrete labels**

Acted emotion database with 1,167 sentences recorded by 12 professional actors. Covers 6 basic emotions from Ekman's model (happiness, sadness, anger, fear, disgust, surprise). Uses a discrete classification scheme.

- **Authors:** Torres Neto, Jose Rodrigues; Rocha Filho, Geraldo Pereira; Mano, Leandro Yukio; Ueyama, Jó
- **Download:** [GitHub Repository](https://github.com/jrtorresneto/VERBO-emotional-speech-dataset)
- **Paper:** [USP Repository](https://repositorio.usp.br/item/002928871)

---

### emoUERJ (2021)
**Acted · 4 emotions · 377 clips · Balanced classes**

Small emotion corpus with 377 audio clips across 4 categories: happiness (91), anger (94), sadness (100), and neutral (92). Balanced per-class distribution.

- **Authors:** No paper related
- **Download:** [Zenodo](https://zenodo.records/5427549)

---

### CORAA SER (2022)
**Natural speech · 3 classes · ~50 min · Gender-aware labels**

~50 minutes of labeled audio segments in 3 classes: neutral, non-neutral female, and non-neutral male. Derived from naturalistic speech rather than acted performances — useful for real-world SER research.

- **Authors:** Workshop of PROPOR 2022
- **Download:** [GitHub Repository](https://github.com/rmarcacini/ser-coraa-pt-br/)
- **Workshop:** [SER 2022](https://sites.google.com/view/ser2022/home)

---

### BADEM (2022)
**Acted · Discrete emotions + neutral · 12 actors · 1,008 recordings · Audio-visual**

Audio-visual acted emotion dataset with 1,008 recordings (84 videos per actor) from 12 actors (6M/6F). Each actor performed 12 sentences per discrete emotion plus neutral. Includes video for multimodal research.

- **Authors:** Luisa Medina Fermino Carlos
- **Download:** [OSF Storage](https://osf.io/68q9m/files/osfstorage)
- **Thesis:** [PDF](https://mestrado.institutopar.org/wp-content/uploads/sites/2/2024/04/Luisa-Medina-2022.pdf)

---

## Automatic Speaker Verification (ASV)

---
---

### BRSpeech-DF-Dataset
**Real & synthetic speech · 459K samples · Brazilian & European Portuguese · Deepfake detection & speaker verification**

459,000 audio samples of real and synthetic speech in Portuguese, covering both Brazilian and European variants. Synthetic samples are generated using multiple zero-shot TTS models, making the dataset suitable for deepfake speech detection and speaker verification research.

- **GitHub:** [AKCIT-Speech/BRSpeech-DF-Dataset](https://github.com/AKCIT-Speech/BRSpeech-DF-Dataset)
- **Download:** [Hugging Face](https://huggingface.co/datasets/AKCIT-Deepfake/BRSpeech-DF)

---

## Gesture Synthesis

---
---

### BRG-Unicamp
> ⚠️ Not yet publicly available

Brazilian Portuguese gesture synthesis dataset from AI-Unicamp.

- **Project page:** [ai-unicamp.github.io/BRG-Unicamp](https://ai-unicamp.github.io/BRG-Unicamp/)

---

## Facial Synthesis

---
---

### Unicamp Facial Synthesis Dataset
> ⚠️ Not yet publicly available

Facial synthesis dataset from Unicamp repository.

- **Repository:** [Unicamp Acervo](https://repositorio.unicamp.br/acervo/detalhe/945977)