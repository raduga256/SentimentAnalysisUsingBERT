[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1iTKkt2y6pTNJ0qWXMG0wki7zUcIpc12S#scrollTo=wbGAsxfqARrK)
# SentimentAnalysisUsingBERT
Build a sentiment classification model using BERT from the Transformers library by Hugging Face with PyTorch and Python.

## Goal
Intuitively understand what BERT is
Preprocess text data for BERT and build PyTorch Dataset (tokenization, attention masks, and padding)
Use Transfer Learning to build Sentiment Classifier using the Transformers library by Hugging Face
Evaluate the model on test data
Predict sentiment on raw text

Learn more about what BERT is, how to use it, and fine-tune it for sentiment analysis on Google Play app reviews. How good will your model be?

## Data Description
You are provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. 
The types of toxicity are:
toxic
severe_toxic
obscene
threat
insult
identity_hate
You must create a model which predicts a probability of each type of toxicity for each comment.

## Tasks
 What is BERT?
(​)  Notebook progress review
(​)  Load BERT using Hugging Face
(​)  Create a Sentiment Classifier using Transfer Learning and BERT
(​)  Training the model
(​)  Evaluation  - how good our model is?
(​)  Predicting sentiment from raw text

## Data Precocessing
You might already know that Machine Learning models don’t work with raw text. You need to convert text to numbers (of some sort). BERT requires even more attention (good one, right?). Here are the requirements:

Add special tokens to separate sentences and do classification
Pass sequences of constant length (introduce padding)
Create array of 0s (pad token) and 1s (real token) called attention mask
The Transformers library provides (you’ve guessed it) a wide variety of Transformer models (including BERT). It works with TensorFlow and PyTorch! It also includes prebuild tokenizers that do the heavy lifting for us!
