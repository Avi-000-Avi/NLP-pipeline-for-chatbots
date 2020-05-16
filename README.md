# NLP-pipeline-for-chatbots

The (hypothetical) restaurant chain has a website with their menu, history, location, hours, and other information, and they would like to add the ability for a website visitor to ask a question in a query box, and have our deep learning NLP chatbot find the relevant information and present that back. They think that getting the right information back to the website visitor quickly would help drive in-store visits and improve the general customer experience.

Objective
To build a chatbot that understands the context (intent) and can also extract the entities. To do this, we need an NLP pipeline that can perform intent classification, along with NER extraction to then provide an accurate response.


Rasa NLU is a Natural Language Understanding tool for understanding a text; in particular, what is being said in short pieces of text. 

Installing Rasa
  
  pip3 install rasa_nlu --quiet --user
  pip3 install coloredlogs sklearn_crfsuite spacy --quiet --user
  python3 -m spacy download en --quiet --user

