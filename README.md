# Corpus 
Nesta sección pode acceder a distintos corpus de texto ou voz en galego (monolingües e multilingües), que poden ser adaptados para diferentes tarefas. Todos estes recursos poden ser descargados con licenzas libres a partir do noso site en [Zenodo](https://zenodo.org/communities/proxecto-nos/?page=1&size=20). Zenodo é un repositorio aberto de uso xeral administrado polo CERN e desenvolvido no ámbito do programa europeo OpenAIRE: rede de repositorios, arquivos e periódicos de acceso aberto que apoia as políticas de acceso aberto na Europa.

In this section you can access different corpora of text or voice in Galician (monolingual and multilingual), which can be adapted for different tasks. All these resources can be downloaded with free licenses from our [Zenodo](https://zenodo.org/communities/proxecto-nos/?page=1&size=20) site. Zenodo is an open repository for general use administered by CERN and developed in the scope of the European program OpenAIRE: a network of repositories, archives and open access journals that supports the policies of open access in Europe.

## Recoñecemento da fala (ASR)

Nesta sección describimos corpus de texto e voz aliñados que poden empregarse para adestrar ou avaliar sistemas de recoñecemento da fala (ASR). Para este fin, o material sonoro debe segmentarse e aliñarse co texto correspondente, tarefa que pode realizarse de forma manual ou automática (aliñamento forzado). 
A continuación detallamos os corpus en galego para ASR desenvolvidos dentro do Proxecto Nós. 

### Nos_ParlaSpeech-GL

Corpus de voz para ASR (texto e voz aliñados), con aliñamento automático, cun total de máis de 1500 horas, creado a partir das sesións plenarias celebradas no Parlamento de Galicia entre os anos 2015 e 2022.

O corpus divídese en dous subcorpus, “clean” e “other”, que constan de XX e XX horas respectivamente. Os segmentos incluídos en “clean” foron filtrados de acordo con varios criterios de calidade, mentres que o subcorpus “other” recolle os segmentos descartados neste filtrado.

Ademais, cada segmento asóciase co identificador do falante correspondente. Os metadatos dos distintos locutores, recollidos dentro do proxecto [ParlaMint-GL](https://github.com/clarin-eric/ParlaMint), pódense consultar neste [enlace](https://github.com/clarin-eric/ParlaMint/tree/main/Data/ParlaMint-ES-GA).

O corpus está dispoñible nos formatos .stm e .json, e os ficheiros de audio no formato WAV a 16 kHz e 16 bits.

### Nos_TranscriSpeech-GL

Corpus de voz para ASR (texto e voz aliñados) de dominio variado, con transcrición e aliñamento manuais e cun total de 53 horas.

O corpus divídese en catro subcorpus temáticos: Conferencias, Entrevistas, Debates e Discursos.

Os ficheiros de audio contidos no corpus están dispoñibles en formato WAV, e os ficheiros de texto aliñado en formato .stm e .trf. Acompáñase o corpus dos metadatos para cada locutor, cando estes son coñecidos, e da guía empregada na realización das transcricións.


| Nome do Corpus       | Lingua/s       | Transcrición          | Aliñamento             | Detalles                      | Descargar (Zenodo) |
| ---------------------| -------------- | --------------------- | ---------------------- |------------------------------ |--------------------|                
| Nos_ParlaSpeech-GL   | gl             | Manual (Parlamento)   | Forzado                | ~1.800 horas (~1M segmentos)  | [url]()            |
| Nos_TranscriSpeech-GL| gl             | Manual (ad-hoc)       | Manual                 | 53 horas (~40.000 segmentos)  | [url]()            |


## Síntese de voz (TTS)

Neste apartado describimos corpus de voz deseñados para o adestramento de sistemas de síntese de voz (TTS) en galego. Para este fin, o texto a ser gravado debe ser coidadosamente seleccionado para ser balanceado e representativo, e as gravacións deben ser de alta calidade e sen ruídos. A continuación detallamos os corpus en galego para TTS desenvolvidos dentro do Proxecto Nós.

### Nos_Celtia-GL

Corpus de voz monolingüe monolocutor para TTS cun total de 30 horas.

Nos_Celtia-GL é un corpus fonética e morfosintacticamente balanceado de 20.000 frases (aproximadamente 200.000 palabras) integrado por dous subcorpus: un corpus previo creado polo Grupo de Tecnoloxías Multimedia (GTM), en colaboración co Centro Ramón Piñeiro para a Investigación en Humanidades (CRPIH) e un corpus elaborado dentro do Proxecto Nós a partir de textos de dominio variado.

O corpus foi gravado por unha voz feminina profesional escollida entre catro locutoras a partir dun test perceptivo realizado por máis de 50 persoas con mostras de catro voces onde se valoraba a claridade, a entoación, a agradabilidade e o nivel de lingua.

Os arquivos de son están dispoñibles no mesmo formato da gravación orixinal: 48 kHz e 16 bits en formato WAV e teñen unha duración de aproximadamente 30 horas.


| Nome do Corpus        | Lingua/s       | Detalles                     | Descargar (Zenodo)                |
| --------------------  | -------------- | -----------------------------|---------------------------------- |
| Nos_Celtia-GL         | gl             |  ~30 horas (20.000 frases)   | [url]()                           |


## Tradución automática

### Corpus bilingües paralelos que inclúen o galego

Neste apartado describimos corpus de traducións humanas (paralelos) que inclúen o galego. Existen dous tipos de corpus paralelos en galego: auténticos e sintéticos. Os primeiros son aqueles que foron realizados por humanos entre o galego e outra lingua, p.e. castelán ou inglés. E os segundos son aqueles transformados artificialmente desde outra variante ou lingua para o galego mediante o uso de diferentes técnicas (p.e. tradución de portugués a galego con transliteración). A continuación detallamos os diferentes corpus paralelos en galego liberados con licenzas libres no Proxecto Nós:

| Nome do Corpus  | Lingua/s       | Auténtico / Sintético | Detalles      | Descargar (Zenodo) |
| --------------  | -------------- | --------------------- | --------------|------------------- |
| Nos_ES-GL_aut   | es-gl_aut      | Auténtico             | 36M de frases |                    |
| Nos_EN-GL_aut   | en-gl-aut      | Auténtico             | 14M de frases |                    |
| Nos_ES-GL_sin   | es-gl_sin      | Sintético             | 35M de frases |                    |
| Nos_EN-GL_sin   | es-gl_sin      | Sintético             | 29M de frases |                    |


+ Nos_ES-GL-aut inclúe os seguintes subcorpus: ccmatrix, cluvi, gnome, kde, paracrawl, ubuntu, wikimedia, wikimatrix, opensubtitles-es-gl, ted2020, opensubtitles2018. 
+ Nos_EN-GL_aut inclúe os seguintes subcorpus: ccmatrix, wikimatrix, opus-en-pt_gl, cluvi.
+ Nos_ES-GL_sin inclúe os seguintes subcorpus: europarl-es-pt_gl, opensubtitles-es-pt_gl, dgt-es-pt_gl, corgabak.
+ Nos_EN-GL_sin inclúe os seguintes subcorpus: opensub-en-pt_gl, europarl-en-pt_gl, ted2020-en-pt_gl, corgaback.


### Corpus de avaliación

| Nome do Corpus      | Lingua/s             | Detalles      | Descargar (Zenodo) |
| ------------------------- | -------------- | ------------- | -------------------|
| Nos_MT_Gold-ES-GL_1       | es-gl          | 1998 frases   |         [url](https://zenodo.org/record/7657887#.Y_OvX9LMJ3k)        |
| Nos_MT_Gold-ES-GL_2       | en-gl          | 1998 frases   |         [url](https://zenodo.org/record/7657993#.Y_Ozr9LMJ3k)        |
| Nos_MT_Gold-EN-GL_1       | en-gl          | 1777 frases   |         [url](https://zenodo.org/record/7658009#.Y_O0x9LMJ3k)        |
| Nos_MT_Gold-EN-GL_2       | en-gl          | 1777 frases   |         [url](https://zenodo.org/record/7658033#.Y_O2o9LMJ3k)        |
| Nos_MT_Test-suite-ES-GL   | en-gl          | 334  frases   |         [url](https://zenodo.org/record/7658052#.Y_O4fNLMJ3k)        |
| Nos_MT_Test-suite-EN-GL   | en-gl          | 364  frases   |         [url](https://zenodo.org/record/7658249#.Y_O6bdLMJ3k)        |

## Outros recursos

#### Corpus nun dominio específico:
Obtivéronse dous datasets de máis de 3000 pares de datos tabulares aliñados con comentarios descritivos, un para o castelán e outro para o galego. O corpus en galego é o primeiro corpus para sistemas Data-To-Text en galego coñecido. Estes datasets foron obtidos a partir da base de datos de MeteoGalicia que conta con datos meteorolóxicos dos últimos 10 anos e textos descritivos bilingües escritos polos expertos meteorólogos pertencentes á institución. Cada un dos [datasets](https://zenodo.org/record/7661650#.Y_dJH9LMJH5) foi revisado e anotado manualmente para incrementar a súa calidade textual e editado para limitar as descricións a aqueles fenómenos relacionados directamente cos datos numéricos. 

#### Corpus de avaliación sintáctica:
Desenvolvéronse os primeiros recursos públicos para a avaliación das capacidades sintácticas e semánticas de modelos de lingua para galego e portugués. As avaliacións tanto sintácticas como semánticas dos modelos neuronais do galego mostran que teñen desempeños similares a modelos equivalentes para outras linguas ([Dataset](https://github.com/marcospln/PROPOR2022-gl-pt), [Modelos avaliados](https://github.com/marcospln/galician_bert_checkpoints)).

#### Corpus de composición semántica:
Dataset empregado por equipos de diversas partes do mundo para o modelado semántico de expresións multipalabra en galego. A introdución deste dataset galego no evento SemEval 2022 (Task 2) permitiu que equipos de todo o mundo traballasen no modelado semántico en galego ([Dataset](https://github.com/H-TayyarMadabushi/SemEval_2022_Task2-idiomaticity)).

