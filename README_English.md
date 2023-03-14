# Corpus 

In this section you can find several text and speech corpora in Galician (both monolingual and multilingual) that can be adapted for different tasks. All these resources can be downloaded under an open-source license from this [Zenodo](https://zenodo.org/communities/proxecto-nos/?page=1&size=20) site. Zenodo is a general-purpose open repository managed by CERN and developed in the area of the European program OpenAIRE: an open-source network for repositories, files and journals that support open-source policies in Europe. 

## Automatic Speech Recognition (ASR)

This section describes aligned speech and text corpora that can be used to train or evaluate Automatic Speech Recognition (ASR) systems. To this end, the audio must be segmented and aligned (manually or automatically – the latter also known as forced alignment) with the corresponding text. Galician ASR corpora developed within the Nós Project are described below.

### Nos_ParlaSpeech-GL

ASR corpus of more than 1,600 hours of automatically aligned speech and text, created from audio and official transcripts of Galician parliamentary sessions celebrated between 2015 and 2022.

The corpus is divided into two subcorpora, “clean” and “other”, consisting of 1,196.92 hours (667,308 segments) and 477.71 hours (130,332 segments), respectively. The segments included in the “clean” subcorpus were filtered according to several alignment quality criteria, whereas the “other” subcorpus comprises the segments that were discarded in the filtering process. 

In addition, each segment is marked with the corresponding speaker ID. Metadata of the different speakers compiled within the [ParlaMint-GL](https://github.com/clarin-eric/ParlaMint) project can be accessed by clicking this [link](https://github.com/clarin-eric/ParlaMint/tree/main/Data/ParlaMint-ES-GA). 

The corpus is available in .stm and .json formats, and audio files in WAV format (16 kHz, 16-bit).

### Nos_TranscriSpeech-GL

Manually transcribed and speech-to-text aligned Galician ASR corpus containing 53 hours of multi-domain speech. 

The corpus is divided into four thematic subcorpora: conferences, interviews, debates and speeches. 

Audio files within the corpus are available in WAV format and aligned text files in .stm and .trf formats. Moreover, the corpus is accompanied by the corresponding speaker metadata and the guide that was used for the manual transcription.


| Corpus Name          | Language/s     | Transcription         | Alignment              | Details                       | Download (Zenodo)  |
| ---------------------| -------------- | --------------------- | ---------------------- |------------------------------ |--------------------|                
| Nos_ParlaSpeech-GL   | gl             | Manual (Parliament)   | Forced                 | ~1,700 hours (~1M segments)   | [url]()            |
| Nos_TranscriSpeech-GL| gl             | Manual (ad hoc)       | Manual                 | 53 hours (~40,000 segments)   | [url](https://zenodo.org/record/7717140)            |


## Speech Synthesis (TTS)

This section describes speech corpora designed for training TTS systems in Galician. To this end, the text to be recorded must be carefully selected in order to be balanced and representative, and the recordings must be high-quality and noise-free. Galician TTS corpora developed within the Nós Project are described below.

### Nos_Celtia-GL

Galician TTS single speaker corpus of approximately 25 hours of speech.

Nos_Celtia-GL is a phonetically and morphosintactically balanced corpus of 20,000 sentences (approximately 200,000 words) consisting of two subcorpora: a previously compiled corpus created by Multimedia Technology Group (GTM) in colaboration with CRPIH (Centro Ramón Piñeiro de Investigación en Humanidades, literally in English, “Ramón Piñeiro Center in Humanities Research”), and a corpus compiled by the Nós Project from multi-domain texts.

The corpus was recorded in a controlled environment (recording studio) by a professional female voice talent selected among four speakers through a perceptual test in which more than 50 participants assessed the speakers’ clarity, prosody, likeability, and language proficiency.

Audio files are available in the original recording format (48 kHz, 16-bit WAV format) and they have a duration of 25 hours approximately.


| Corpus Name           | Language/s     | Details                        | Download (Zenodo)                 |
| --------------------  | -------------- | -------------------------------|---------------------------------- |
| Nos_Celtia-GL         | gl             |  ~25 hours (20,000 sentences)  | [url](https://zenodo.org/record/7716958#.ZAtZm3bMJD8)                           |


## Machine Translation

### Bilingual parallel texts including Galician

In this section, parallel texts made of human translations including Galician language are described. There are two types of parallel texts in Galician: authentic and synthetic. The first ones are those made by human translators from or into Galician and another language, such as English or Spanish. Synthetic parallel texts are those artificially transformed from another language into Galician through different techniques (for example, machine translation and transliteration from Portuguese into Galician). The different parallel texts including Galician and published under a free license by the Nós project are listed below:

| Corpus Name     | Language/s     | Authentic / Synthetic | Details         | Download (Zenodo)  |
| --------------  | -------------- | --------------------- | ----------------|------------------- |
| Nos_ES-GL_aut   | es-gl          | Authentic             | 36M sentences   |     [url](https://zenodo.org/record/7671278#.Y_j109LMJH4)               |
| Nos_EN-GL_aut   | en-gl          | Authentic             | 14M sentences   |     [url](https://zenodo.org/record/7675110#.Y_yBh9LML_o)               |
| Nos_ES-GL_sin   | es-gl          | Synthetic             | 35M sentences   |     [url](-)               |
| Nos_EN-GL_sin   | en-gl          | Synthetic             | 29M sentences   |     [url](-)               |


+ Nos_ES-GL-aut includes the following subcorpora: ccmatrix, cluvi, gnome, kde, paracrawl, ubuntu, wikimedia, wikimatrix, opensubtitles-es-gl, ted2020, opensubtitles2018. 
+ Nos_EN-GL_aut includes the following subcorpora: ccmatrix, wikimatrix, opus-en-pt_gl, cluvi.
+ Nos_ES-GL_sin includes the following subcorpora: europarl-es-pt_gl, opensubtitles-es-pt_gl, dgt-es-pt_gl.
+ Nos_EN-GL_sin includes the following subcorpora: opensub-en-pt_gl, europarl-en-pt_gl, ted2020-en-pt_gl.


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
Two datasets including more than 3,000 tabular data pairs aligned with descriptive comments were obtained, one for Spanish and another for Galician. The Galician corpus is the first Galician corpus for Data-to-Text systems known. These datasets were obtained through the database MeteoGalicia, which includes meteorological data from the last 10 years together with descriptive bilingual texts written by expert meteorologists from the same institution. Each dataset was manually reviewed and annotated to improve its linguistic quality and was edited to delimit descriptions to only those phenomena directly related to numeric data. Hereafter you can find the [dataset](https://zenodo.org/record/7661650#.Y_dJH9LMJH5).

#### Syntactic evaluation corpora:
Public resources for the evaluation of syntactic and semantic abilities of language models for Galician and Portuguese were developed. Evaluations of neural models for Galician, both syntactic and semantic, show they perform similarly to equivalent models for other languages. Here you can access the datasets ([syntactic](https://github.com/marcospln/PROPOR2022-gl-pt) and [semantic](https://github.com/marcospln/homonymy_acl21)), and the [evaluated systems](https://github.com/marcospln/galician_bert_checkpoints).

#### Semantic composition corpus:
Dataset for semantic evaluation of multiword expressions modeling in Galician. The introduction of this dataset in the SemEval 2022 (Task 2) event allowed international teams to work on the semantic modeling in Galician. Here you can access the [dataset](https://github.com/H-TayyarMadabushi/SemEval_2022_Task2-idiomaticity).
