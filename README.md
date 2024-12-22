# SMS Spam Classification

## Overview

This project implements a spam classification system for SMS messages using machine learning techniques. It utilizes different vectorization methods and Naive Bayes classifiers to classify messages as "spam" or "ham."

## Features

- **Preprocessing**: Text data is cleaned and prepared by removing stop words, punctuation, and numbers.
- **Vectorization**: Uses Count Vectorizer (binary and frequency) and TF-IDF Vectorizer to convert text data into numerical features.
- **Classification**: Trains and evaluates models using Bernoulli Naive Bayes and Multinomial Naive Bayes classifiers.
- **Evaluation**: Assesses model performance with accuracy scores, classification reports, and confusion matrices.

## Files

- `sms_spam.csv`: Dataset used for training and testing the model.
- `Sentiment-Analysis-Project-on-SMSDataset-in ML.pynb`: notebook containing the complete code for data preprocessing, vectorization, model training, and evaluation.

## Requirements

- Python 3.x
- Pandas
- NLTK
- scikit-learn
- Joblib
