# Sentiment Analysis on Twitter Data

## Project Overview

This project focuses on sentiment analysis using Natural Language Processing (NLP) techniques applied to Twitter data. Sentiment analysis is the process of determining the emotional tone behind a piece of text, and in this case, we are analyzing sentiments expressed in tweets.

## Data Preprocessing

The data is preprocessed for better analysis. The preprocessing includes converting the data to lowercase, removing punctuation, stopwords, etc.

## Sentiment Analysis

The sentiment analysis task is carried out using two different methods:

1) Lexicon-based Method:

We employ the SentimentIntensityAnalyzer from the Natural Language Toolkit (NLTK) library to perform sentiment analysis based on lexicons. This approach assigns sentiment scores to each tweet by analyzing the words' polarity and intensity in the text.

2) Machine Learning Method - Support Vector Machine (SVM):

We utilize a machine learning model based on the Support Vector Machine (SVM) algorithm. For feature extraction and vectorization of the tweet data, we use the Term Frequency-Inverse Document Frequency (TF-IDF) method. SVM is trained on the TF-IDF vectors and then used to predict the sentiment of tweets.

## Visualization

Plotly, a Python library for interactive visualization, is used to create visual representations of the sentiment analysis results.

## Evaluation

The performance of both the lexicon-based method and the SVM-based method is evaluated using appropriate metrics, such as the confusion matrix, accuracy, and AUC ROC.
