# Corpora 
Nesta sección pode acceder a distintos corpora de texto ou voz (monolingües en galego e multilingües), que pode adaptar para as súas tarefas. Todos estes recursos poden ser descargados a partir do site Zenodo, sendo Zenodo un repositorio aberto de uso xeral administrado polo CERN e desenvolvido no ámbito do programa europeo OpenAIRE: rede de repositorios, arquivos e periódicos de acceso aberto que apoia as políticas de acceso aberto na Europa.

In this section you can access different text or voice corpus (Galician monolingual and multilingual) that you can adapt to your tasks. All these resources can be downloaded from the Zenodo site, being Zenodo an open repository of general use operated by CERN and developed within the scope of the European programme OpenAIRE: a network of open access repositories, archives and journals supporting open access policies in Europe.

## Voz

### ASR (Recoñecemento de fala)

**Corpus de voz do Parlamento de Galicia:** Corpus de voz para ASR (texto e voz aliñados) creado a partir dos datos do Parlamento. 

**Corpus de voz do ILG:** Corpus de voz para ASR (texto e voz aliñados) creado a partir dos datos do ILG. 

### TTS (Síntese de fala)

**Voz Proxecto Nós:** Corpus de voz para TTS (1 locutora).

**Mostra TTS voz feminina:** Mostra de voz de 4 locutoras para test perceptual (selección da voz máis axeitada para TTS).

## Texto

### Corpus monolingües en galego

Neste apartado están os diferentes corpus monolingües en galego que poden ser utilizados para diferentes tarefas. 

**Corpus monolingüe textual escala web (Nos_GL_WEB):** 

Compilouse un corpus textual a escala web, que inclúe texto xornalístico, administrativo, enciclopédico, e de redes sociais. Este recurso ten máis de 550 millóns de palabras (máis de 633 millóns de tokens), e está en constante ampliación, limpeza, e organización. Para alén de compilarmos o recurso en formato texto, foi procesado con ferramentas computacionais para a súa etiquetaxe lingüística (lematización, anotación morfosintáctica, e análise sintáctica de dependencias). 

**Novo corpus web para o galego (Nos_GL_WEB_CCNET):** 

Foi elaborado un corpus textual do galego a partir do crawling da web e, a partir deste, foi construído un modelo de lingua en formato SentencePiece. Estes desenvolvementos foron levados a cabo mediante o uso das ferramentas e datos do proxecto CCNet, de Meta/Facebook. Tanto o corpus como o modelo están dispoñíbeis baixo licenzas libres.  


| Nome do Corpus  | Lingua/s       | Auténtico / Sintético | Detalles                         | Descargar (Zenodo)  |
| --------------  | -------------- | --------------------- | -------------------------------- |-------------------  |
| Nos_GL_WEB      | GL             | Auténtico             | 555M palabras / 633M tokens      |                     |
| Nos_GL_WEB_CCNET| GL             | Auténtico             | 555M palabras / 633M tokens      |                     |


### Corpus bilingües en galego

Os corpus paralelos son corpus de traducións humanas entre galego e outras linguas, necesarios para adestrar por exemplo sistemas de tradución automática. Existen dous tipos de corpus paralelos en galego: auténticos e sintéticos. Os primeiros son aqueles que foron realizados por humanos entre o galego e outra lingua, p.e. castelán ou inglés. Os segundos son aqueles transformados para galego mediante diferentes técnicas (p.e. tradución de portugués a galego con transliteración). A continuación detallamos os diferentes corpus paralelos en galego liberados con licenzas libres no Proxecto Nós:

| Nome do Corpus  | Lingua/s       | Auténtico / Sintético | Detalles                         | Descargar (Zenodo) |
| --------------  | -------------- | --------------------- | -------------------------------- |------------------- |
| Nos_ES-GL       | GL-ES          | Auténtico             | 15M de frases                    |                    |
| Nos_EN-GL       | GL-EN          | Auténtico             | 30M de frases                    |                    |
| Nos_ES-GL_PT    | GL_PT-ES       | Sintético             | 30M de frases                    |                    |
| Nos_EN-GL_PT    | GL_PT-EN       | Sintético             | 30M de frases                    |                    |



### Outros corpus

**Corpus nun dominio específico:**
Obtivéronse dous datasets de máis de 3000 pares de datos tabulares aliñados con comentarios descritivos, un para o castelán e outro para o galego. O corpus en galego é o primeiro corpus para sistemas Data-To-Text en galego coñecido. Estes datasets foron obtidos a partir da base de datos de MeteoGalicia que conta con datos meteorolóxicos dos últimos 10 anos e textos descritivos bilingües escritos polos expertos meteorólogos pertencentes á institución. Cada un dos datasets foi revisado e anotado manualmente para incrementar a súa calidade textual e editado para limitar as descricións a aqueles fenómenos relacionados directamente cos datos numéricos. 

**Corpus de avaliación sintáctica:** 
Desenvolvéronse os primeiros recursos públicos para a avaliación das capacidades sintácticas e semánticas de modelos de lingua para galego e portugués. As avaliacións tanto sintácticas como semánticas dos modelos neuronais do galego mostran que teñen desempeños similares a modelos equivalentes para outras linguas. 

**Corpus de composición semántica:** 
Dataset empregado por equipos de diversas partes do mundo para o modelado semántico de expresións multipalabra en galego. A introdución deste dataset galego no evento SemEval 2022 (Task 2) permitiu que equipos de todo o mundo traballasen no modelado semántico en galego (https://github.com/H-TayyarMadabushi/SemEval_2022_Task2-idiomaticity)

