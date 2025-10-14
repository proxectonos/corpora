# Corpus 

In this section you can find several text and speech corpora in Galician (both monolingual and multilingual) that can be adapted for different tasks. All these resources can be downloaded under an open-source license from this [Zenodo](https://zenodo.org/communities/proxecto-nos/?page=1&size=20) site. Zenodo is a general-purpose open repository managed by CERN and developed in the area of the European program OpenAIRE: an open-source network for repositories, files and journals that support open-source policies in Europe. 

## Text corpus (Massive Corpus)

### Nos_CorpusNOS-GL

CorpusNÓS is a massive Galician corpus made up of 2.1B words primarily devised for training large language models. The corpus sources are varied and represent a relatively wide range of genres.

The corpus is structured as follows:

| Subcorpus                             | Genre               | Nº tokens      | Nº documents |
|---------------------------------------|---------------------|----------------|--------------|
| Data obtained via transfer agreement  | Books               | 7,255,784      | 104          |
|                                       | Research articles   | 2,665,351      | 664          |
|                                       | Press               | 124,253,084    | 224,419      |
|                                       | Governmental        | 245,897,880    | 654,505      |
|                                       | Web contents        | 15,946,686     | 44,165       |
|                                       | Encyclopedic        | 4,799,214      | 47,396       |
|                                       | Subtotal            | 400,817,999    | 971,253      |

| Subcorpus                             | Genre               | Nº tokens      | Nº documents |
|---------------------------------------|---------------------|----------------|--------------|
| Public data                           | Press and blogs     | 153,497,883    | 665,265      |
|                                       | Encyclopedic        | 57,164,848     | 184,628      |
|                                       | Web crawls          | 1,384,015,664  | 3,366,449    |
|                                       | Translation corpora | 133,726,004    | 4,745,799    |
|                                       | Subtotal            | 1,728,404,399  | 8,777,514    |
|                                       | Total               | 2,129,222,398  | 9,748,767    |
| Download (Zenodo)                     | https://zenodo.org/records/10687642                 |                                    



Following this structure, the corpus contains two folders for each subcorpus and within each subcorpus, folders with the different genres can be found. Files are in plain text format (*.txt) and individual documents inside each file are separated by two line breaks.

Note: Some of the files referenced may be missing in this version of the corpus due to pending transfer agreements and they will be included in a future version of the corpus as soon as they are available for publishing.

Note: Please, note that the following subcorpora have different licenses which correspond to their original licenses as specified in the paper: TED2020 (CC BY–NC–ND 4.0), mC4 (Apache License 2.0), OSCAR (CC0).

If you use CorpusNÓS for your work, please, cite as:

de-Dios-Flores, Iria, Silvia Paniagua Suárez, Cristina Carbajal Pérez, Daniel Bardanca Outeiriño, Marcos Garcia and Pablo Gamallo. 2024. CorpusNÓS: A massive Galician corpus for training large language models. Proceedings of the 16th International Conference on Computational Processing of Portuguese - ACL Anthology (Volume 1), 593-599.

https://aclanthology.org/2024.propor-1.66.pdf

## Automatic Speech Recognition (ASR)

This section describes aligned speech and text corpora that can be used to train or evaluate Automatic Speech Recognition (ASR) systems. To this end, the audio must be segmented and aligned (manually or automatically – the latter also known as forced alignment) with the corresponding text. Galician ASR corpora developed within the Nós Project are described below.

### Nos_ParlaSpeech-GL

ASR corpus of more than 1,600 hours of automatically aligned speech and text, created from audio and official transcripts of Galician parliamentary sessions celebrated between 2015 and 2022.

The corpus is divided into two subcorpora, “clean” and “other”, consisting of 1,196.92 hours (667,308 segments) and 477.71 hours (130,332 segments), respectively. The segments included in the “clean” subcorpus were filtered according to several alignment quality criteria, whereas the “other” subcorpus comprises the segments that were discarded in the filtering process. 

In addition, each segment is marked with the corresponding speaker ID. Metadata of the different speakers compiled within the [ParlaMint](https://github.com/clarin-eric/ParlaMint) project can be accessed by clicking this [link](https://github.com/clarin-eric/ParlaMint/tree/main/Samples/ParlaMint-ES-GA). 

The corpus is available in STM and JSON formats, and audio files in WAV format (16 kHz, 16-bit).

### Nos_TranscriSpeech-GL

Manually transcribed and speech-to-text aligned Galician ASR corpus containing 53 hours of multi-domain speech. 

The corpus is divided into four thematic subcorpora: conferences, interviews, debates and speeches. 

Audio files within the corpus are available in WAV format and aligned text files in STM and TRF formats. Moreover, the corpus is accompanied by the corresponding speaker metadata and the guide that was used for the manual transcription.

### Nos_RG-Podcast-GL
Automatically transcribed and speech-to-text aligned Galician dataset of 328 hours, designed for automatic speech recognition (ASR) tasks. It includes 33 podcast series in Galician, organized into seven main genres: culture, society, history, equality, science, humor, and fiction. The following table provides the title, genre, number of episodes, and total duration of each program. 

| Title                            | Genre          | No. of episodes  | Total duration of program (h)  |                       
| -------------------------------- | -------------- | ---------------- | ------------------------------ |                
| 21-dias-co-galego                | culture        | 23               | 4,329                          | 
| a-fin-do-mundo                   | society        | 5                | 3,781                          | 
| apalabradas                      | society        | 33               | 9,872                          |                    
| arqueoloxia-historia             | history        | 16               | 2,749                          |                    
| arte                             | culture        | 20               | 2,526                          |                    
| teatro-artes-escenicas           | culture        | 20               | 2,628                          |                    
| audiovisual                      | culture        | 30               | 5,008                          |                    
| como-que-non                     | humor          | 76               | 77,672                         |                    
| consellos-con-sexo               | equality       | 25               | 5,983                          |                    
| deborah-ciencia                  | science        | 28               | 6,7914                         |                    
| efemirdas                        | history        | 28               | 6,078                          |                    
| enfermeira-saturada              | science        | 27               | 6,279                          |   
| escoitamos-teatro                | culture        | 6                | 2,735                          |   
| florencio-o-poeta-de-valdeorras  | culture        | 5                | 1,398                          |   
| galicia-para-neofalantes         | culture        | 9                | 1,646                          |   
| lambóns-de-viaxe                 | culture        | 5                | 4,568                          |   
| libros                           | culture        | 47               | 7,813                          |   
| medio-ambiente                   | society        | 43               | 12,085                         |      
| moito-ollo                       | equality       | 20               | 8,651                          |     
| morra-o-conto                    | equality       | 35               | 4,422                          |     
| morte-na-abadia                  | fiction        | 1                | 0,320                          |     
| o-barroquista                    | history        | 45               | 10,049                         |     
| o-impostor                       | humor          | 8                | 7,319                          |     
| o-poigrama                       | society        | 44               | 10,503                         |     
| os-pobres-si-que-choran          | fiction        | 62               | 8,734                          |     
| paseo-polo-museo                 | culture        | 1                | 0,655                          |     
| poesia                           | culture        | 35               | 4,972                          |     
| proxima-estacion                 | history        | 6                | 1,247                          |     
| start-up-galicia                 | society        | 5                | 2,043                          | 
| superando-a-ficcion              | society        | 21               | 7,920                          | 
| un-ollo-de-vidro                 | fiction        | 7                | 3,004                          | 
| zeta                             | culture        | 88               | 94,248                         | 


The dataset is divided into three partitions “train”, “dev” and “test”, consisting of 259,078 hours, 14,541 hours and 14,537 hours, respectively. 
The original version of this dataset, in STM format and non-segmented audio, can be found in Zenodo (soon).  


| Corpus Name          | Language/s     | Transcription         | Alignment              | Details                       | Download (Zenodo)  |
| ---------------------| -------------- | --------------------- | ---------------------- |------------------------------ |--------------------|                
| Nos_ParlaSpeech-GL   | gl             | Manual (Parliament)   | Forced                 | ~1,700 hours (~1M segments)   | [URL](https://zenodo.org/record/7913218) |
| Nos_TranscriSpeech-GL| gl             | Manual (ad hoc)       | Manual                 | 53 hours (~40,000 segments)   | [URL](https://zenodo.org/record/7717140) |
| Nos_RG-Podcast-GL    | gl             | Forced (ad hoc)       | Forced                 | 328 hours                     | Soon|


## Speech Synthesis (TTS)

This section describes speech corpora designed for training TTS systems in Galician. To this end, the text to be recorded must be carefully selected in order to be balanced and representative, and the recordings must be high-quality and noise-free. Galician TTS corpora developed within the Nós Project are described below.

### Nos_Celtia-GL

Galician TTS single speaker corpus of approximately 25 hours of speech.

Nos_Celtia-GL is a phonetically and morphosintactically balanced corpus of 20,000 sentences (approximately 200,000 words) consisting of two subcorpora: a previously compiled corpus created by Multimedia Technology Group (GTM) in colaboration with CRPIH (Centro Ramón Piñeiro de Investigación en Humanidades, literally in English, “Ramón Piñeiro Center in Humanities Research”), and a corpus compiled by the Nós Project from multi-domain texts.

The corpus was recorded in a controlled environment (recording studio) by a professional female voice talent selected among four speakers through a perceptual test in which more than 50 participants assessed the speakers’ clarity, prosody, likeability, and language proficiency.

Audio files are available in the original recording format (48 kHz, 16-bit WAV format) and they have a duration of 25 hours approximately.

### Nos_Brais-GL
Galician TTS single speaker corpus of approximately 18 hours of speech. 

Nos_Brais-GL is based on a phonetically and morphosyntactically rich text corpus of 16,121 sentences (approximately 168,000 words) comprising three subcorpora: selected phrases from a corpus compiled by the Nós Project from multi-domain texts and previously used in the Nos_Celtia-GL TTS corpus; selected phrases from a previously compiled corpus created by the Multimedia Technology Group (GTM) and the CRPIH (Centro Ramón Piñeiro para a Investigación en Humanidades); and, finally, a 500-word phonetically rich single-word subcorpus extracted from the Pronunciation dictionary of the Galician language (Dicionario de pronuncia da lingua galega). 

Nos_Brais-GL was recorded in a controlled environment (recording studio) by a professional male voice talent selected among three speakers through a perceptual listening test in which 37 participants assessed the speakers’ clarity, prosody, likeability and language proficiency.

The audio files are available in the original recording format (48 kHz, 24-bit WAV format) and they have a duration about 18 hours approximately. 

| Corpus Name           | Language/s     | Details                        | Download (Zenodo)                 |
| --------------------  | -------------- | -------------------------------|---------------------------------- |
| Nos_Celtia-GL         | gl             |  ~25 hours (20,000 sentences)  | [URL](https://zenodo.org/record/7716958#.ZAtZm3bMJD8)                           |
| Nos_Brais-GL          | gl             |  ~18 hours (16,121 sentences)  | [URL](https://zenodo.org/records/8027725)                                       |


## Machine Translation

### Bilingual parallel texts including Galician

In this section, parallel texts made of human translations including Galician language are described. There are two types of parallel texts in Galician: authentic and synthetic. The first ones are those made by human translators from or into Galician and another language, such as English or Spanish. Synthetic parallel texts are those artificially transformed from another language into Galician through different techniques (for example, machine translation and transliteration from Portuguese into Galician). The different parallel texts including Galician and published under a free license by the Nós project are listed below:

| Corpus Name     | Language/s     | Authentic / Synthetic | Details         | Download (Zenodo)  |
| --------------  | -------------- | --------------------- | ----------------|------------------- |
| Nos_ES-GL_aut   | es-gl          | Authentic             | 36M sentences   |     [URL](https://zenodo.org/record/7671278#.Y_j109LMJH4)               |
| Nos_EN-GL_aut   | en-gl          | Authentic             | 14M sentences   |     [URL](https://zenodo.org/record/7675110#.Y_yBh9LML_o)               |
| Nos_ES-GL_sin   | es-gl          | Synthetic             | 35M sentences   |     [URL](-)               |
| Nos_EN-GL_sin   | en-gl          | Synthetic             | 29M sentences   |     [URL](-)               |


+ Nos_ES-GL-aut includes the following subcorpora: ccmatrix, cluvi, gnome, kde, paracrawl, ubuntu, wikimedia, wikimatrix, opensubtitles-es-gl, ted2020, opensubtitles2018. 
+ Nos_EN-GL_aut includes the following subcorpora: ccmatrix, wikimatrix, opus-en-pt_gl, cluvi.
+ Nos_ES-GL_sin includes the following subcorpora: europarl-es-pt_gl, opensubtitles-es-pt_gl, dgt-es-pt_gl.
+ Nos_EN-GL_sin includes the following subcorpora: opensub-en-pt_gl, europarl-en-pt_gl, ted2020-en-pt_gl.


### Evaluation parallel texts

| Corpus Name               | Language/s     | Details        | Download (Zenodo)  |
| ------------------------- | -------------- | ---------------| -------------------|
| Nos_MT_Gold-ES-GL_1       | es-gl          | 1998 sentences |         [URL](https://zenodo.org/record/7657887#.Y_OvX9LMJ3k)        |
| Nos_MT_Gold-ES-GL_2       | es-gl          | 1998 sentences |         [URL](https://zenodo.org/record/7657993#.Y_Ozr9LMJ3k)        |
| Nos_MT_Gold-EN-GL_1       | en-gl          | 1777 sentences |         [URL](https://zenodo.org/record/7658009#.Y_O0x9LMJ3k)        |
| Nos_MT_Gold-EN-GL_2       | en-gl          | 1777 sentences |         [URL](https://zenodo.org/record/7658033#.Y_O2o9LMJ3k)        |
| Nos_MT_Test-suite-ES-GL   | es-gl          | 334 sentences  |         [URL](https://zenodo.org/record/7658052#.Y_O4fNLMJ3k)        |
| Nos_MT_Test-suite-EN-GL   | en-gl          | 364 sentences  |         [URL](https://zenodo.org/record/7658249#.Y_O6bdLMJ3k)        |

## Other resources

#### Specific domain corpora:
Two datasets including more than 3,000 tabular data pairs aligned with descriptive comments were obtained, one for Spanish and another for Galician. The Galician corpus is the first Galician corpus for Data-to-Text systems known. These datasets were obtained through the database MeteoGalicia, which includes meteorological data from the last 10 years together with descriptive bilingual texts written by expert meteorologists from the same institution. Each dataset was manually reviewed and annotated to improve its linguistic quality and was edited to delimit descriptions to only those phenomena directly related to numeric data. Hereafter you can find the [dataset](https://zenodo.org/record/7661650#.Y_dJH9LMJH5).

#### Syntactic evaluation corpora:
Public resources for the evaluation of syntactic and semantic abilities of language models for Galician and Portuguese were developed. Evaluations of neural models for Galician, both syntactic and semantic, show they perform similarly to equivalent models for other languages. Here you can access the datasets ([syntactic](https://github.com/marcospln/PROPOR2022-gl-pt) and [semantic](https://github.com/marcospln/homonymy_acl21)), and the [evaluated systems](https://github.com/marcospln/galician_bert_checkpoints).

#### Semantic composition corpus:
Dataset for semantic evaluation of multiword expressions modeling in Galician. The introduction of this dataset in the SemEval 2022 (Task 2) event allowed international teams to work on the semantic modeling in Galician. Here you can access the [dataset](https://github.com/H-TayyarMadabushi/SemEval_2022_Task2-idiomaticity).

#### CC0 Sentence Corpus (nos_gl_CC0):
Copyright-free [(CC0)](https://creativecommons.org/publicdomain/zero/1.0/legalcode) sentences in Galician, collected by [Proxecto Nós](nos.gal) in order to contribute to the text corpus of [Mozilla Common Voice](https://commonvoice.mozilla.org/gl/). You can access the data [here](https://github.com/proxectonos/nos_gl_CC0/tree/main).
