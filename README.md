# Preprocesing-with-SpaCy and Rasa_nlu
  * Learning how to use the library spaCy to preprocessing data 
  
# Intent Classification with Rasa NLU and SpaCy
  * A Libary for intent recognition and entity extraction based on SpaCy and Sklearn
  
*NLP = NLU+NLG*
  * NLP = Natural Language “Processing” (understand,process,interprete everyday human language)
  * NLU = Natural Language “Understanding” (unstructured inputs and convert them into a structured form that a machine can understand and           act upon)
  * NLG = Natural Language “Generation” (responding the same way a human would have by generating artificial text that looks like what a human would have said)
  
 
![](https://github.com/iyeedinho/preprocesing-with-SpaCy-and-Rasa-nlu/blob/master/dif.png)

***Installation***

*   pip install rasa_nlu
*   python -m rasa_nlu.server &
*   sklearn_crfsuite




 ***using spacy as backend***


*   pip install rasa_nlu[spacy]
*   python -m spacy download en_core_web_md
*   python -m spacy link en_core_web_md en

***Using Datasets***

1.   Demo-rasa.json
2.   Config_spacy.yaml
