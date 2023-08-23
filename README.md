# NER-Gum
Named Entity Recognition for GUM

The purpose of this project is to analyze the Georgetown University Multilayer (GUM) Corpus coming from this repo (https://github.com/nluninja/nlp_datasets/tree/main/GUM), that contains two columns:
- token
- ner_tag

  
This corpus contains English texts from twelve written and spoken text types:
- interviews
- news
- travel guides
- how-to guides
- academic writing
- biographies
- fiction
- online forum discussions
- spontaneous face to face conversations
- political speeches
- textbooks
- vlogs

  
Our goal is to classify correctly the 23 classes coming from the ner_tag through a BILSTM and Bert Model
