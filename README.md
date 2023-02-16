# Corpus 
Nesta sección pode acceder a distintos corpus de texto ou voz en galego (monolingües e multilingües), que poden ser adaptados para diferentes tarefas. Todos estes recursos poden ser descargados con licenzas libres a partir do site Zenodo (https://zenodo.org/communities/proxecto-nos/?page=1&size=20), sendo Zenodo un repositorio aberto de uso xeral administrado polo CERN e desenvolvido no ámbito do programa europeo OpenAIRE: rede de repositorios, arquivos e periódicos de acceso aberto que apoia as políticas de acceso aberto na Europa.

In this section you can access different corpora of text or voice in Galician (monolingual and multilingual), which can be adapted for different tasks. All these resources can be downloaded with free licenses from the Zenodo site (https://zenodo.org/communities/proxecto-nos/?page=1&size=20), Zenodo being an open repository for general use administered by CERN and developed in the scope of the European program OpenAIRE: a network of repositories, archives and open access journals that supports the policies of open access in Europe.

## Voz

### ASR (Recoñecemento de fala)

**Corpus de voz do Parlamento de Galicia:** Corpus de voz para ASR (texto e voz aliñados) creado a partir dos datos do Parlamento. 

**Corpus de voz do ILG:** Corpus de voz para ASR (texto e voz aliñados) creado a partir dos datos do ILG. 

### TTS (Síntese de fala)

**Voz Proxecto Nós:** Corpus de voz para TTS (1 locutora).

**Mostra TTS voz feminina:** Mostra de voz de 4 locutoras para test perceptual (selección da voz máis axeitada para TTS).

## Texto

### Tradución automática

#### Corpus bilingües paralelos que inclúen o galego

Neste apartado describimos corpus de traducións humanas (paralelos) que inclúen o galego. Existen dous tipos de corpus paralelos en galego: auténticos e sintéticos. Os primeiros son aqueles que foron realizados por humanos entre o galego e outra lingua, p.e. castelán ou inglés. E os segundos son aqueles transformados artificialmente desde outra variante ou lingua para o galego mediante o uso de diferentes técnicas (p.e. tradución de portugués a galego con transliteración). A continuación detallamos os diferentes corpus paralelos en galego liberados con licenzas libres no Proxecto Nós:

| Nome do Corpus  | Lingua/s       | Auténtico / Sintético | Detalles      | Subcorpus          |Descargar (Zenodo) |
| --------------  | -------------- | --------------------- | --------------|------------------- |                   |
| Nos_ES-GL-aut   | es-gl_aut         | Auténtico             | 71M de frases | ccmatrix,cluvi,gnome,kde,paracrawl,ubuntu,wikimedia,wikimatrix,opensubtitles-es-gl,ted2020,opensubtitles2018                   |                   |
| Nos_EN-GL_aut   | en-gl-aut         | Auténtico             | 30M de frases |                    |                   |
ccmatrix,wikimatrix,cluvi
| Nos_ES-GL_sin   | es-gl_sin       | Sintético             | 30M de frases |                    |                   |
europarl-es-pt_gl,opensubtitles-es-pt_gl,dgt-es-pt_gl,corgabak
| Nos_EN-GL_sin   | es-gl_sin       | Sintético             | 30M de frases |                    |                   |
opensub-en-pt_gl,europarl-en-pt_gl,opus-en-pt_gl,ted2020-en-pt_gl,corgabak

#### Corpus de avaliación

| Nome do Corpus      | Lingua/s             | Detalles      | Descargar (Zenodo) |
| ------------------------- | -------------- | ------------- | -------------------|
| Nos_MT_Gold-ES-GL_1       | es-gl          | 1998 frases   |                    |
| Nos_MT_Gold-ES-GL_2       | en-gl          | 1998 frases   |                    |
| Nos_MT_Gold-EN-GL_1       | en-gl          | 1777 frases   |                    |
| Nos_MT_Gold-EN-GL_2       | en-gl          | 1777 frases   |                    |
| Nos_MT_Test-suite-ES-GL   | en-gl          | 334  frases   |                    |
| Nos_MT_Test-suite-EN-GL   | en-gl          | 364 frases    |                    |

### Outros recursos

**Corpus nun dominio específico:**
Obtivéronse dous datasets de máis de 3000 pares de datos tabulares aliñados con comentarios descritivos, un para o castelán e outro para o galego. O corpus en galego é o primeiro corpus para sistemas Data-To-Text en galego coñecido. Estes datasets foron obtidos a partir da base de datos de MeteoGalicia que conta con datos meteorolóxicos dos últimos 10 anos e textos descritivos bilingües escritos polos expertos meteorólogos pertencentes á institución. Cada un dos datasets foi revisado e anotado manualmente para incrementar a súa calidade textual e editado para limitar as descricións a aqueles fenómenos relacionados directamente cos datos numéricos. 

**Corpus de avaliación sintáctica:** 
Desenvolvéronse os primeiros recursos públicos para a avaliación das capacidades sintácticas e semánticas de modelos de lingua para galego e portugués. As avaliacións tanto sintácticas como semánticas dos modelos neuronais do galego mostran que teñen desempeños similares a modelos equivalentes para outras linguas (https://github.com/marcospln/galician_bert_checkpoints).

**Corpus de composición semántica:** 
Dataset empregado por equipos de diversas partes do mundo para o modelado semántico de expresións multipalabra en galego. A introdución deste dataset galego no evento SemEval 2022 (Task 2) permitiu que equipos de todo o mundo traballasen no modelado semántico en galego (https://github.com/H-TayyarMadabushi/SemEval_2022_Task2-idiomaticity)

