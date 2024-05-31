# PRODIGY_DS_04
Sentiment Analysis using Logistic Regression

## Sentiment Analysis of Twitter Data
This project demonstrates how to perform sentiment analysis on Twitter data using a logistic regression model. The dataset used for this analysis is from Kaggle's "Twitter Sentiment Analysis" dataset, which includes labeled tweets categorized as Positive, Negative, or Neutral.

## What is Sentiment Analysis?
Sentiment analysis, also known as opinion mining, is a technique used to determine the sentiment expressed in a piece of text. It involves identifying whether the sentiment is positive, negative, or neutral. This is particularly useful for understanding public opinion towards specific topics, brands, or products.

## Dataset
The dataset consists of two CSV files:

twitter_training.csv: The training set.
twitter_validation.csv: The validation set.
Each file contains the following columns:

id: The ID of the tweet.
information: Additional information about the tweet.
type: The sentiment label (Positive, Negative, Neutral).
text: The text of the tweet.

## Steps
1. Import libraries
2. Load Dataset
3. Add column names
4. Function to clean text and apply cleaning
5. Emcode sentiment labels
6. Vectorize text data
7. Initialize and Train model
8. Make predictions
9. Visualize

## Vectorizer:
A vectorizer is a tool that converts text data into numerical feature vectors that can be used by machine learning algorithms. In this project, we use CountVectorizer from scikit-learn, which:

Tokenizes the text (splits it into words).
Builds a vocabulary of known words.
Encodes new text using this vocabulary, creating a feature vector for each text document.
