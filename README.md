# Data-Science-Final-Project
Mental Health Assistance Deep Learning/NLP Based Chatbot

A chatbot is a piece of intelligent software that can interact with users in a way that is similar to how a human might. Chatbots are frequently employed in customer service, social media marketing, and instant messaging with customers. Based on their construction, chatbot models can be divided into two categories: retrieval-based models and generative-based models.

1. Retrieval Based Chatbots:
A chatbot that relies on retrieval employs predefined input and response patterns. After that, it chooses the right response using a heuristic method. Goal-oriented chatbots are frequently created using this technique, and we may alter their tone and natural flow to provide our consumers with the greatest possible service.

2. Generative Based Chatbots:
Generative models don't rely on any predetermined answers.
Seq 2 Seq neural networks serve as their foundation. The concept is similar to machine translation. Unlike machine translation, where we convert source code from one language to another, here we will convert input into output. It relies on deep neural networks and requires a lot of data.

In this Python project (Chatbot.ipynb), I have build a chatbot using deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. We use a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.

We have created a retrieval based chatbot using NLTK, Keras, Python, etc.

The dataset we will be using is ‘intents.json’. This is a JSON file that contains the patterns we need to find and the responses we want to return to the user.

I have created a Mental Health Assistance Chatbot with a Graphic User Interface to Chat with the Medical Bot.
