English text [here](https://github.com/proxectonos/corpora/blob/main/README_English.md)

# Corpus
Nesta sección podes acceder a distintos corpus de texto ou voz en galego (monolingües e multilingües), que poden ser adaptados para diferentes tarefas. Todos estes recursos poden ser descargados con licenzas libres a partir do noso site en [Zenodo](https://zenodo.org/communities/proxecto-nos/?page=1&size=20). Zenodo é un repositorio aberto de uso xeral administrado polo CERN e desenvolvido no ámbito do programa europeo OpenAIRE: rede de repositorios, arquivos e periódicos de acceso aberto que apoia as políticas de acceso aberto na Europa.

## Corpus de texto (Macrocorpus)

### Nos_CorpusNOS-GL

CorpusNÓS é un corpus masivo para a lingua galega composto por 2.1 mil millóns palabras principalmente deseñado para adestrar modelos de linguaxe grandes. As fontes do corpus son variadas e representan unha ampla gama de xéneros.

O corpus está estruturado da seguinte maneira:

| Subcorpus                             | Xénero              | Nº de tokens    | Nº de documentos |
|---------------------------------------|---------------------|-----------------|------------------|
| Datos obtidos mediante acordo de transferencia | Libros              | 7,255,784        | 104              |
|                                       | Artigos de investigación | 2,665,351     | 664              |
|                                       | Prensa              | 124,253,084      | 224,419          |
|                                       | Gubernamental       | 245,897,880      | 654,505          |
|                                       | Contidos web       | 15,946,686       | 44,165           |
|                                       | Enciclopédico       | 4,799,214        | 47,396           |
|                                       | Subtotal           | 400,817,999      | 971,253          |

| Subcorpus                             | Xénero              | Nº de tokens    | Nº de documentos |
|---------------------------------------|---------------------|-----------------|------------------|
| Datos públicos                        | Prensa e blogs      | 153,497,883      | 665,265          |
|                                       | Enciclopédico       | 57,164,848       | 184,628          |
|                                       | Rastrexos web      | 1,384,015,664    | 3,366,449        |
|                                       | Corpus de tradución | 133,726,004    | 4,745,799        |
|                                       | Subtotal           | 1,728,404,399    | 8,777,514        |
|                                       | Total              | 2,129,222,398    | 9,748,767        |
| Descarga (Zenodo)                     | https://zenodo.org/records/10687642             |      


Seguindo esta estrutura, o corpus contén dúas carpetas para cada subcorpus e dentro de cada subcorpus, pódense atopar carpetas cos diferentes xéneros. Os ficheiros están en formato de texto plano (*.txt) e os documentos individuais dentro de cada ficheiro están separados por dous saltos de liña.

Nota: Algúns dos ficheiros referidos poden faltar nesta versión do corpus debido a acordos de transferencia pendentes e serán incluídos nunha versión futura do corpus en canto estean dispoñibles para a súa publicación.   

Se usas o CorpusNÓS para o teu traballo, por favor, cita a seguinte publicación:

de-Dios-Flores, Iria, Silvia Paniagua Suárez, Cristina Carbajal Pérez, Daniel Bardanca Outeiriño, Marcos Garcia and Pablo Gamallo. 2024. CorpusNÓS: A massive Galician corpus for training large language models. Proceedings of the 16th International Conference on Computational Processing of Portuguese - ACL Anthology (Volume 1), 593-599.

https://aclanthology.org/2024.propor-1.66.pdf

## Recoñecemento da fala (ASR)

Neste apartado describimos corpus de texto e voz aliñados que poden empregarse para adestrar ou avaliar sistemas de recoñecemento da fala (ASR). Para este fin, o material sonoro debe segmentarse e aliñarse co texto correspondente, tarefa que pode realizarse de forma manual ou automática (aliñamento forzado). 
A continuación detallamos os corpus en galego para ASR desenvolvidos dentro do Proxecto Nós. 

### Nos_ParlaSpeech-GL

Corpus de voz para ASR (texto e voz aliñados), con aliñamento automático, cun total de máis de 1600 horas, creado a partir das sesións plenarias celebradas no Parlamento de Galicia entre os anos 2015 e 2022.

O corpus divídese en dous subcorpus, “clean” e “other”, que constan de 1.196,92 horas (667.308 segmentos) e 477,71 horas (130.332 segmentos) respectivamente. Os segmentos incluídos en “clean” foron filtrados de acordo con varios criterios de calidade, mentres que o subcorpus “other” recolle os segmentos descartados neste filtrado.

Ademais, cada segmento asóciase co identificador do falante correspondente. Os metadatos dos distintos locutores, recollidos dentro do proxecto [ParlaMint](https://github.com/clarin-eric/ParlaMint), pódense consultar nesta [ligazón](https://github.com/clarin-eric/ParlaMint/tree/main/Samples/ParlaMint-ES-GA).

O corpus está dispoñible nos formatos STM e JSON, e os ficheiros de audio en formato WAV a 16 kHz e 16 bits.

### Nos_TranscriSpeech-GL

Corpus de voz para ASR (texto e voz aliñados) de dominio variado, con transcrición e aliñamento manuais e cun total de 53 horas.

O corpus divídese en catro subcorpus temáticos: Conferencias, Entrevistas, Debates e Discursos.

Os ficheiros de audio contidos no corpus están dispoñibles en formato WAV a 44.1 kHz e 16 bits, e os ficheiros de texto aliñado en formato STM e TRF. Acompáñase o corpus dos metadatos para cada locutor e da guía empregada na realización das transcricións.


| Nome do Corpus       | Lingua/s       | Transcrición          | Aliñamento             | Detalles                      | Descargar (Zenodo) |
| ---------------------| -------------- | --------------------- | ---------------------- |------------------------------ |--------------------|                
| Nos_ParlaSpeech-GL   | gl             | Manual (Parlamento)   | Forzado                | ~1.700 horas (~1M segmentos)  | [URL](https://zenodo.org/record/7913218) |
| Nos_TranscriSpeech-GL| gl             | Manual (ad-hoc)       | Manual                 | 53 horas (~40.000 segmentos)  | [URL](https://zenodo.org/record/7717140) |


## Síntese de voz (TTS)

Neste apartado describimos corpus de voz deseñados para o adestramento de sistemas de síntese de voz (TTS) en galego. Para este fin, o texto a ser gravado debe ser coidadosamente seleccionado para ser balanceado e representativo, e as gravacións deben ser de alta calidade e sen ruídos. A continuación detallamos os corpus en galego para TTS desenvolvidos dentro do Proxecto Nós.

### Nos_Celtia-GL

Corpus de voz monolingüe monolocutor para TTS cun total de 25 horas.

Nos_Celtia-GL é un corpus fonética e morfosintacticamente balanceado de 20.000 frases (aproximadamente 200.000 palabras) integrado por dous subcorpus: un corpus previo creado polo Grupo de Tecnoloxías Multimedia (GTM), en colaboración co Centro Ramón Piñeiro para a Investigación en Humanidades (CRPIH) e un corpus elaborado dentro do Proxecto Nós a partir de textos de dominio variado.

O corpus foi gravado nun ambiente controlado (estudio de gravación) por unha voz feminina profesional escollida entre catro locutoras a partir dun test perceptivo realizado por máis de 50 persoas con mostras de catro voces onde se valoraba a claridade, a entoación, a agradabilidade e o nivel de lingua.

Os arquivos de son están dispoñibles no mesmo formato da gravación orixinal: 48 kHz e 16 bits en formato WAV e teñen unha duración de aproximadamente 25 horas.


| Nome do Corpus        | Lingua/s       | Detalles                     | Descargar (Zenodo)                |
| --------------------  | -------------- | -----------------------------|---------------------------------- |
| Nos_Celtia-GL         | gl             |  ~25 horas (20.000 frases)   | [URL](https://zenodo.org/record/7716958#.ZAtZm3bMJD8)                           |


## Tradución automática

### Corpus bilingües paralelos que inclúen o galego

Neste apartado describimos corpus de traducións humanas (paralelos) que inclúen o galego. Existen dous tipos de corpus paralelos en galego: auténticos e sintéticos. Os primeiros son aqueles que foron realizados por humanos entre o galego e outra lingua, p.e. castelán ou inglés. E os segundos son aqueles transformados artificialmente desde outra variante ou lingua para o galego mediante o uso de diferentes técnicas (p.e. tradución de portugués a galego con transliteración). A continuación detallamos os diferentes corpus paralelos en galego liberados con licenzas libres no Proxecto Nós:

| Nome do Corpus  | Lingua/s  | Auténtico / Sintético | Detalles        | Descargar (Zenodo) |
| --------------  | --------- | --------------------- | ----------------|------------------- |
| Nos_ES-GL_aut   | es-gl     | Auténtico             | 36M de oracións | [URL](https://zenodo.org/record/7671278#.Y_j109LMJH4)                   |
| Nos_EN-GL_aut   | en-gl     | Auténtico             | 14M de oracións | [URL](https://zenodo.org/record/7675110#.Y_yBh9LML_o)                   |
| Nos_ES-GL_sin   | es-gl     | Sintético             | 35M de oracións | [URL](https://zenodo.org/record/7691829#.ZD-ml9IzZH4)                   |
| Nos_EN-GL_sin   | en-gl     | Sintético             | 29M de oracións | [URL](https://zenodo.org/record/7685180#.ZD-mp9IzZH4)                   |


+ Nos_ES-GL-aut inclúe os seguintes subcorpus: ccmatrix, cluvi, gnome, kde, paracrawl, ubuntu, wikimedia, wikimatrix, opensubtitles-es-gl, ted2020, opensubtitles2018. 
+ Nos_EN-GL_aut inclúe os seguintes subcorpus: ccmatrix, wikimatrix, cluvi.
+ Nos_ES-GL_sin inclúe os seguintes subcorpus: europarl-es-pt_gl, opensubtitles-es-pt_gl, dgt-es-pt_gl.
+ Nos_EN-GL_sin inclúe os seguintes subcorpus: opensub-en-pt_gl, europarl-en-pt_gl, opus-en-pt_gl, ted2020-en-pt_gl.


### Corpus de avaliación

| Nome do Corpus      | Lingua/s             | Detalles      | Descargar (Zenodo) |
| ------------------------- | -------------- | ------------- | -------------------|
| Nos_MT_Gold-ES-GL_1       | es-gl          | 1998 oracións |         [URL](https://zenodo.org/record/7657887#.Y_OvX9LMJ3k)        |
| Nos_MT_Gold-ES-GL_2       | en-gl          | 1998 oracións |         [URL](https://zenodo.org/record/7657993#.Y_Ozr9LMJ3k)        |
| Nos_MT_Gold-EN-GL_1       | en-gl          | 1777 oracións |         [URL](https://zenodo.org/record/7658009#.Y_O0x9LMJ3k)        |
| Nos_MT_Gold-EN-GL_2       | en-gl          | 1777 oracións |         [URL](https://zenodo.org/record/7658033#.Y_O2o9LMJ3k)        |
| Nos_MT_Test-suite-ES-GL   | en-gl          | 334  oracións |         [URL](https://zenodo.org/record/7658052#.Y_O4fNLMJ3k)        |
| Nos_MT_Test-suite-EN-GL   | en-gl          | 364  oracións |         [URL](https://zenodo.org/record/7658249#.Y_O6bdLMJ3k)        |

## Outros recursos

#### Corpus nun dominio específico:
Obtivéronse dous datasets de máis de 3000 pares de datos tabulares aliñados con comentarios descritivos, un para o castelán e outro para o galego. O corpus en galego é o primeiro corpus para sistemas Data-To-Text en galego coñecido. Estes datasets foron obtidos a partir da base de datos de MeteoGalicia que conta con datos meteorolóxicos dos últimos 10 anos e textos descritivos bilingües escritos polos expertos meteorólogos pertencentes á institución. Cada un dos datasets foi revisado e anotado manualmente para incrementar a súa calidade textual e editado para limitar as descricións a aqueles fenómenos relacionados directamente cos datos numéricos. Aqui podes acceder ao [dataset](https://zenodo.org/record/7661650#.Y_dJH9LMJH5).

#### Corpus de avaliación sintáctica:
Desenvolvéronse recursos públicos para a avaliación das capacidades sintácticas e semánticas de modelos de lingua para galego e portugués. As avaliacións tanto sintácticas como semánticas dos modelos neuronais do galego mostran que teñen desempeños similares a modelos equivalentes para outras linguas. Aqui podes acceder aos datasets ([sintáctico](https://github.com/marcospln/PROPOR2022-gl-pt) e [semántico](https://github.com/marcospln/homonymy_acl21)) e aos [modelos avaliados](https://github.com/marcospln/galician_bert_checkpoints).

#### Corpus de composición semántica:
Dataset de avaliación semántica de expresións multipalabra en galego. A introdución deste dataset galego no evento SemEval 2022 (Task 2) permitiu que equipos internacionais traballasen no modelado semántico en galego. Aqui podes acceder ao [dataset](https://github.com/H-TayyarMadabushi/SemEval_2022_Task2-idiomaticity).

#### Corpus de frases con licenza CC0 (nos_gl_CC0):
Frases con licenza libre [(CC0)](https://creativecommons.org/publicdomain/zero/1.0/legalcode) en galego, recollidas co fin de alimentar o corpus textual de [Mozilla Common Voice](https://commonvoice.mozilla.org/gl/). Podes acceder ao corpus [aquí](https://github.com/proxectonos/nos_gl_CC0/tree/main).
