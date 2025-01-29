# Sentiment Analysis of Black Lives Matter Tweets

## Project Overview
This project aims to analyze sentiments expressed in tweets related to the Black Lives Matter movement. Utilizing a dataset of 100,000 tweets, this analysis identifies whether a tweet supports or opposes the movement. The primary focus is on applying and comparing various machine learning and deep learning techniques to accurately classify tweet sentiments.

## Dataset
The dataset comprises 100,000 English tweets, divided into 80,000 for training and 20,000 for testing, with a balanced class distribution of positive and negative sentiments.

## Features
- **Retweet Count:** Significant in differentiating between sentiments.
- **Tweet Length:** Positive tweets tend to be longer.
- **Word Embeddings and TF-IDF Vectorization:** Used to transform text into numerical data.

## Models Evaluated
- **Machine Learning Models:** Linear SVC, Random Forest, Multinomial Naive Bayes, K-Neighbors, and SGD Classifier.
- **Deep Learning Models:** Basic LSTM and enhanced LSTM with convolutional layers.

## Performance
The best-performing model was the SGD Classifier with an accuracy of 93.87% on the test dataset.

## Key Insights
- **Feature Importance:** Retweet count significantly impacts sentiment classification.
- **Model Efficacy:** TF-IDF vectorization was more effective than word embeddings for this dataset.

## Usage
Details on how to use the scripts, train models, and perform your own sentiment analysis are provided in subsequent sections of this README.

## Contributions
Contributions are welcome, especially in the areas of model enhancement, feature engineering, and expanding the dataset.

