# Deep-Learning-RNN-Tasks

## Overview
This repository contains three deep learning tasks, each involving a different application of Recurrent Neural Networks (RNNs). The tasks focus on time series prediction, text generation, and contextual embedding using advanced RNN techniques. Each task is implemented separately, with detailed comparisons and analyses of various neural network architectures and techniques.

## Tasks

### 1. Stock Market Prediction
Using RNNs, the task is to predict the stock prices of Apple (AAPL) and Google (GOOG) based on historical data. The objective is to build and compare the performance of different RNN architectures (LSTM, GRU, RNN) and measure the accuracy of predictions using metrics such as MSE and MAPE. Additionally, the impact of various optimizers (Adam, RMSprop, ADAgrad) and regularization methods like dropout are evaluated.

### 2. Text Generation
The goal is to design an RNN-based model capable of generating new text based on a dataset of the book *Harry Potter and the Goblet of Fire*. The model generates characters, and the performance is evaluated based on model accuracy and loss metrics. The task involves tuning parameters such as the number of epochs and using different loss functions to optimize performance.

### 3. Contextual Embedding + RNNs
This task involves using RNNs combined with contextual embeddings like BERT or HateBERT to classify textual data collected from Twitter into three categories: Normal, Offensive, and Hate. The task includes data preprocessing, building an LSTM or GRU-based model, and evaluating the performance using confusion matrices and other evaluation metrics.

## Methods
Each task utilizes different RNN architectures (LSTM, GRU, Vanilla RNN) and compares their performances based on evaluation metrics. Various techniques like embedding layers, contextual embeddings (BERT, HateBERT), and different optimizers are applied to enhance the model's performance.

## Hyperparameter Tuning
For each task, hyperparameter tuning is performed, focusing on:
- Number of epochs
- Learning rate
- Batch size
- Dropout rate
