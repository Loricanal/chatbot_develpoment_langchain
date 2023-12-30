# Chatbot Develpoment Langchain
The repository comprises notebooks from a database course within the Cinema and Media Engineering track at Politecnico di Torino where students developed a chatbot using Langchain. All the notebooks are in Italian since the course language is Italian. They include instructions given to students for various phases of chatbot creation and are divided as follows:

## [Chatbot_Setup.ipynb](https://colab.research.google.com/drive/1sIy6IVzW5ANHoTpWYNXlf9IXlNL3Cw-P?usp=sharing)
Students:
1. Familiarized themselves with Colab Notebooks.
2. Installed necessary Python packages.
3. Created a non-functional Telegram bot by obtaining a key for later connection to the Python code.
4. Selected documents from which the bot extracts information (minimum of 3 documents and a maximum of 6, including at least one webpage and one PDF).
5. Formulated 10 questions to which they assumed the bot should know the answers, manually writing responses used as ground truth for evaluation.

## [Creazione_del_Chatbot.ipynb](https://colab.research.google.com/drive/1X1Pj9ik5qhO1m5_P7Es2vKQ5VJYTEZCf?usp=sharing)
Students initiated the creation of the foundational version of the chatbot (Python code without Telegram integration). They:
1. Employed a preliminary method for document chunking.
2. Used a single embedding model.
3. Integrated a single large language model.
This initial chatbot configuration laid the groundwork for subsequent iterations, providing a baseline for comparison and evaluation. The goal was to create an initial version of the chatbot from start to finish.

## [Scelta_della_configurazione_migliore_del_Chatbot.ipynb](https://colab.research.google.com/drive/1vHXgeznEpwmNfGOXVl3-PeVA8X6sa5cl?usp=sharing)
Students systematically tested 3 different embedding models and 3 large language models, for a total of 9 combinations, evaluating responses to the 10 questions selected in the initial phase for each of them. Their primary objective was to determine the optimal combination that would enhance the chatbot's overall performance. The evaluation criteria included response times, retrieval accuracy, and the quality of the language model's output in terms of semantic pertinence and grammar syntax accuracy.

## [Collegare_il_chatbot_a_Telegram.ipynb](https://colab.research.google.com/drive/1QNuZ00D-LeZHOju_JVmNOB7X3gQRbPSp?usp=sharing)
Following the development of the chatbot logic and functionality, the subsequent step involved seamlessly integrating these features into a Telegram channel. Python code managed the functionalities of the Telegram channel, providing a user-friendly interface for real-time interaction with the chatbot. The goal was to extend the chatbot's accessibility beyond coding environments, making it available on a widely used messaging platform, thereby enhancing its usability and practicality.



