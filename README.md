# Text Sentiment Analysis with LSTM and Custom Embeddings (TensorFlow)
## Introduction

This project focuses on performing sentiment analysis using Long Short-Term Memory (LSTM) networks implemented with TensorFlow. It includes components for text preprocessing and text vectorization using custom word embeddings, this can be used in customer feedback analysis or social media monitoring.

## Features

- Text Preprocessing: Prepares raw text data by performing essential cleaning operations like removing HTML tags, punctuation, and special characters, converting text to lowercase, and lemmatizing words to their root forms.
- Custom Word Embeddings: Generates custom word embeddings using techniques like Word2Vec or GloVe, representing words as dense vectors and capturing their semantic relationships within the training dataset.
- LSTM Model: Builds and trains a Long Short-Term Memory (LSTM) neural network, a type of recurrent neural network (RNN) especially designed to handle sequential data like text. It can capture long-term dependencies within the text, which is important for understanding the sentiment.
- Sentiment Classification: Classifies text into categories, such as positive, negative sentiment.

## Prerequisites

- Python 3.6 or higher.
- Required Python libraries: tensorflow, nltk, scikit-learn, pandas, numpy.
