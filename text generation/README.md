
---

### 2. **Text Generation**

```md
# Text Generation Using RNN

## Overview
This project focuses on generating text based on a dataset from the book *Harry Potter and the Goblet of Fire*. The model is an RNN designed to predict the next character in the sequence.

## Dataset
- **dataset.txt**: Contains text from *Harry Potter and the Goblet of Fire*.
- The dataset is processed character by character for the RNN to learn and generate new text.

## Methods
- **Model**: An RNN model is trained to generate text based on input sequences.
- **Metrics**: The performance is evaluated using loss functions and accuracy.
- **Training**: The model is trained over multiple epochs, with a minimum of 3 epochs for training.
- **Tuning**: Various hyperparameters are tuned, including the number of epochs and learning rate.

## Results
The generated text is evaluated based on the model's accuracy and loss. The quality of text improves as the number of epochs increases.

## How to Run
To run the text generation model:
```bash
python text_generation_rnn.m
