# SentimentAnalysis


A Deep Learning model designed to classify sentiments in movie reviews as either positive or negative. This project leverages Natural Language Processing (NLP) techniques and neural networks to perform sentiment analysis on text data.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project aims to build a sentiment analysis model using deep learning to determine the sentiment expressed in movie reviews. The dataset used for training and evaluation contains labeled reviews with sentiment labels (1 for positive, 0 for negative).

## Features
-**Tokenizer & Padding**: Preprocesses text data by tokenizing words and padding sequences to ensure consistent input length.
-**Deep Learning Model**: LSTM network with dropout layers to handle sequential text data.
-**Binary Sentiment Classification**: Encodes text data for binary classification, predicting positive or negative sentiment.

## Prerequisites
To run this project, the following packages are required:

-tensorflow
-pandas
-scikit-learn

## Project Structure
-**sentiment_analyzer.py**: Contains the main code for the sentiment analysis model.
-**README.md**: Project documentation.
-**data.csv**: Sample training data file (placeholder for actual data)
## Data Requirements
The model expects a CSV file (data.csv) with two columns:

-text: The text or reviews for analysis.
-label: Binary sentiment labels (e.g., 0 for negative, 1 for positive).
## Model Details
The model architecture includes:

-Embedding Layer: Word embedding for vectorizing input text.
-Spatial Dropout Layer: Reduces overfitting by randomly dropping units.
-LSTM Layer: Processes sequential data to capture context.
-Dense Output Layer: Uses sigmoid activation for binary classification.


