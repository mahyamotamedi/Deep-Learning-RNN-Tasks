
---

### 3. **Contextual Embedding + RNNs**

```md
# Contextual Embedding and RNN for Text Classification

## Overview
This project involves using Recurrent Neural Networks (RNNs) combined with contextual embeddings (BERT and HateBERT) to classify textual data into three categories: Normal, Offensive, and Hate.

## Dataset
- **main_data.csv**: Contains raw data collected from Twitter.
- **pre_main_data.csv**: Preprocessed data with labels.
- The data is labeled into three categories: Normal, Offensive, and Hate.

## Methods
- **Model**: The task is performed using an LSTM or GRU-based model with contextual embeddings (BERT or HateBERT).
- **Metrics**: The performance is evaluated using accuracy, loss, and confusion matrices.
- **Embeddings**: Different contextual embeddings (BERT and HateBERT) are used to improve classification performance.

## Results
The models are compared based on their accuracy and loss. The performance of BERT and HateBERT embeddings is analyzed.

## How to Run
To run the text classification model:
```bash
python embedding_lstm.m
