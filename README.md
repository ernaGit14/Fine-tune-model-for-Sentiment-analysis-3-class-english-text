This repository contains a fine-tuned transformer model for 3-class sentiment analysis on English text.
The model classifies input text into the following categories:
1. Positive
2. Neutral
3. Negative

This project uses the j-hartmann/sentiment-roberta-large-english-3-classes model as the base model and fine-tunes it using the dataset data_comment_with_label.csv.
The provided code can also be used to fine-tune the model with any other custom dataset.

For best results, it is recommended to use a balanced dataset, ideally with at least 100 samples per class.
data_comment is the data that we used to test the model.
