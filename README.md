# sDolly-2 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1RGacPC23tMve76exEew9Ex1VLxRl8dLM?authuser=1#scrollTo=7kzrtCy4nFHB)

Welcome to the sDolly GitHub page!

sDolly is a project that is inspired by the Databricks project and trains a Llama model on a Databricks notebook. This project utilizes the GPT-2 model, which is a powerful natural language processing (NLP) model developed by OpenAI.

The GPT-2 model is a neural network language model that can be fine-tuned for specific tasks, such as QA, text summarization or next token prediction. It works by using a multi-layer transformer architecture that allows it to process sequences of text and learn patterns in language. The model is trained on a large corpus of text data, such as books or web pages, and learns to predict the next word in a sentence based on the context of the preceding words.

For next token prediction, the GPT-2 model takes a sequence of words as input and predicts the probability distribution of the next word in the sequence. The word with the highest probability is then selected as the predicted next token. This process is repeated iteratively to generate a sequence of words.

In this project, the GPT-2 model was fine-tuned on a part of the Amazon dataset (https://www.kaggle.com/datasets/praneshmukhopadhyay/amazon-questionanswer-dataset), which is a collection of questions and answers related to various products on Amazon. The distilled model was used to train a model on Google Colab GPUs.

If you want the model weights of the experiment, have a look here: https://drive.google.com/drive/folders/10OFDbkTxHJhaN-oNMXCB9DU9bnj8-4X4?usp=share_link

Thank you for checking out the sDolly prject!
