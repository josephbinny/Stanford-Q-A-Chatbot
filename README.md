# Stanford-Q-A-Chatbot
Interactive chatbot for information extraction from Stanford Q&amp;A dataset

This is part of a project for AAI 520 course in Fall 2023 at the University of San Diego

I built an interactive chatbot leveraging Llama 2 13b chat model. The UI is made with Gradio. Note that there was no fine-tuning of the model. The chain (built with LangChain) uses FAISS to fetch relevant Q&A close to the user's query to feed to the model along with the query to get an appropriate response. Please refer to the code to get a better understanding of the implementation. Note that the chat interface prints the model's response along with the top fetched Q&A pair from the dataset.

The dataset can be found [here](https://www.kaggle.com/datasets/stanfordu/stanford-question-answering-dataset).

*Please note that the code is tested on Google Colab and might require work to adjust for local environments.*
