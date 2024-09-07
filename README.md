# Sentiment Analysis Script

This repository contains a Python script for performing sentiment analysis on a dataset of Amazon product reviews. The script uses the Hugging Face `transformers` library to analyze the sentiment of text data and processes the texts in parallel to enhance efficiency.

## Features

- Load a CSV file containing product reviews.
- Perform sentiment analysis on the review texts using a pre-trained model.
- Process texts in parallel to improve performance.
- Save the results to a new CSV file with sentiment labels and scores.

## Requirements

- Python 3.7 or higher
- `pandas`
- `transformers`
- `concurrent.futures` (included
