# Corpus 

In this section you can find several text and speech corpora in Galician (both monolingual and multilingual) that can be adapted for different tasks. All these resources can be downloaded under an open-source license from this [Zenodo](https://zenodo.org/communities/proxecto-nos/?page=1&size=20) site. Zenodo is a general-purpose open repository managed by CERN and developed in the area of the European program OpenAIRE: an open-source network for repositories, files and journals that support open-source policies in Europe. 

## Automatic Speech Recognition (ASR)

In this section, aligned text and speech corpus are described, which can be used for training or evaluating Automatic Speech Recognition systems (ASR). For this purpose, audio resources must be segmented and aligned together with the corresponding text, a task that can be manually or automatically done (forced alignment). Galician corpora developed within the Nós project for ASR are described below. 

### Nos_ParlaSpeech-GL

Speech corpus for ASR (speech and text aligned) of more than 1,500 hours, made with automatic alignment, and created from plenaries at the Galician Parliament between 2015 and 2022.

The corpus is divided into two subcorpora, “clean” and “other”, containing XX and XX hours respectively. Segments included in the “clean” subcorpus were screened following different quality criteria, whereas the “other” subcorpus contains the rejected segments in the filtering process.

In addition, every segment is linked to the corresponding speaker ID. Metadata of the different speakers compiled within the [ParlaMint-GL](https://github.com/clarin-eric/ParlaMint) project can be found by clicking this [link](https://github.com/clarin-eric/ParlaMint/tree/main/Data/ParlaMint-ES-GA). The corpus is available in .stm and .json formats, and audio files in WAV format (16 kHz, 16 bits).

### Nos_TranscriSpeech-GL

Speech corpus for ASR (speech and text aligned) of different domains, containing 53 hours, with transcriptions and manual alignment. The corpus is divided into four thematic subcorpora: conferences, interviews, debates and speeches. 

Audio files within the corpus are available in WAV format and aligned text files in .stm and .trf formats. The metadata corpus of each speaker (if the speaker is known) and the transcription guide used are added.


| Corpus Name          | Language/s     | Transcription         | Alignment              | Details                       | Download (Zenodo)  |
| ---------------------| -------------- | --------------------- | ---------------------- |------------------------------ |--------------------|                
| Nos_ParlaSpeech-GL   | gl             | Manual (Parliament)   | Forced                 | ~1,800 hours (~1M segments)   | [url]()            |
| Nos_TranscriSpeech-GL| gl             | Manual (ad hoc)       | Manual                 | 53 hours (~40,000 segments)   | [url]()            |


## Speech Synthesis (TTS)

In this section, speech corpora designed to train speech synthesis systems (TTS) in Galician are described. For this purpose, the text to be recorded must be carefully selected, so it is balanced and representative, and recordings must be of high quality and without any noise. Galician corpora for TTS developed within the Nós project are listed below.

### Nos_Celtia-GL

Monolingual speech corpus with only one speaker containing 30 hours for TTS.

Nos_Celtia-GL is a phonetically and morphosintactically balanced corpus of 20,000 sentences (200,000 word approximately) consisting of two subcorpora: an existing corpus created by Multimedia Technology Group (GTM) in colaboration with CRPIH (Centro Ramón Piñeiro de Investigación en Humanidades, literally in English, “Ramón Piñeiro Center in Humanities Research”), and a corpus created from several domain texts within the Nós project.

The corpus was recorded with a professional female voice selected among four speakers through a perceptive test in which 50 people have participated. This test contains four samples with four different voices in which clarity, intonation, likability and language quality were evaluated.

Audio files are available in the original recording format (48 kHz and 16 bits in WAV format) and they have a duration of 30 hours approximately.


| Corpus Name           | Language/s     | Details                        | Download (Zenodo)                 |
| --------------------  | -------------- | -------------------------------|---------------------------------- |
| Nos_Celtia-GL         | gl             |  ~30 hours (20,000 sentences)  | [url]()                           |


## Machine Translation

### Bilingual parallel texts including Galician

In this section, parallel texts made of human translations including Galician language are described. There are two types of parallel texts in Galician: authentic and synthetic. The first ones are those made by human translators from or into Galician and another language, such as English or Spanish. Synthetic parallel texts are those artificially transformed from another language into Galician through different techniques (for example, machine translation and transliteration from Portuguese into Galician). The different parallel texts including Galician and published under a free license by the Nós project are listed below:

| Corpus Name     | Language/s     | Authentic / Synthetic | Details         | Download (Zenodo)  |
| --------------  | -------------- | --------------------- | ----------------|------------------- |
| Nos_ES-GL_aut   | es-gl_aut      | Authentic             | 36M sentences   |     [url](https://zenodo.org/record/7671278#.Y_j109LMJH4)               |
| Nos_EN-GL_aut   | en-gl-aut      | Authentic             | 14M sentences   |     [url](https://zenodo.org/record/7675110#.Y_yBh9LML_o)               |
| Nos_ES-GL_sin   | es-gl_sin      | Synthetic             | 35M sentences   |     [url](https://zenodo.org/record/7674099#.Y_j1odLMJH4)               |
| Nos_EN-GL_sin   | en-gl_sin      | Synthetic             | 29M sentences   |     [url](https://zenodo.org/record/7675473#.Y_yBUtLML_o)               |


+ Nos_ES-GL-aut includes the following subcorpora: ccmatrix, cluvi, gnome, kde, paracrawl, ubuntu, wikimedia, wikimatrix, opensubtitles-es-gl, ted2020, opensubtitles2018. 
+ Nos_EN-GL_aut includes the following subcorpora: ccmatrix, wikimatrix, opus-en-pt_gl, cluvi.
+ Nos_ES-GL_sin includes the following subcorpora: europarl-es-pt_gl, opensubtitles-es-pt_gl, dgt-es-pt_gl, corgabak.
+ Nos_EN-GL_sin includes the following subcorpora: opensub-en-pt_gl, europarl-en-pt_gl, ted2020-en-pt_gl, corgaback.


### Evaluation parallel texts

| Corpus Name               | Language/s     | Details        | Download (Zenodo)  |
| ------------------------- | -------------- | ---------------| -------------------|
| Nos_MT_Gold-ES-GL_1       | es-gl          | 1998 sentences |         [url](https://zenodo.org/record/7657887#.Y_OvX9LMJ3k)        |
| Nos_MT_Gold-ES-GL_2       | es-gl          | 1998 sentences |         [url](https://zenodo.org/record/7657993#.Y_Ozr9LMJ3k)        |
| Nos_MT_Gold-EN-GL_1       | en-gl          | 1777 sentences |         [url](https://zenodo.org/record/7658009#.Y_O0x9LMJ3k)        |
| Nos_MT_Gold-EN-GL_2       | en-gl          | 1777 sentences |         [url](https://zenodo.org/record/7658033#.Y_O2o9LMJ3k)        |
| Nos_MT_Test-suite-ES-GL   | es-gl          | 334 sentences  |         [url](https://zenodo.org/record/7658052#.Y_O4fNLMJ3k)        |
| Nos_MT_Test-suite-EN-GL   | en-gl          | 364 sentences  |         [url](https://zenodo.org/record/7658249#.Y_O6bdLMJ3k)        |

## Other resources

#### Specific domain corpora:
Two datasets including more than 3,000 tabular data pairs aligned with descriptive comments were obtained, one for Spanish and another for Galician. The Galician corpus is the first Galician corpus for Data-to-Text systems known. These datasets were obtained through the database MeteoGalicia, which includes meteorological data from the last 10 years together with descriptive bilingual texts written by expert meteorologists from the same institution. Each dataset was manually reviewed and annotated to improve its linguistic quality and was edited to delimit descriptions to only those phenomena directly related to numeric data. Hereafter you can find the [Dataset](https://zenodo.org/record/7661650#.Y_dJH9LMJH5).

#### Syntactic evaluation corpora:
The first public resources for the evaluation of syntactic and semantic abilities of language models for Galician and Portuguese were developed. Evaluations of neural models for Galician, both syntactic and semantic, show they perform similarly to equivalent models for other languages. Here you can access the [Dataset](https://github.com/marcospln/PROPOR2022-gl-pt) and the [Evaluated systems](https://github.com/marcospln/galician_bert_checkpoints).

#### Semantic composition corpus:
Dataset used by teams from different regions in the world for the semantic modeling of multiword expressions in Galician. The introduction of this dataset in the SemEval 2022 (Task 2) event allowed teams from all over the world to work on the semantic modeling in Galician. Here you can access the [Dataset](https://github.com/H-TayyarMadabushi/SemEval_2022_Task2-idiomaticity).
