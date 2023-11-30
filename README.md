# Sentiment Predictor for Amazon Product Reviews

## Introduction

I have developed a Sentiment Predictor utilizing an Amazon product reviews dataset. The project aims to predict the sentiment of reviews as either positive or negative. This project involved a series of steps, starting from data cleaning and preprocessing to the implementation of various machine learning algorithms for sentiment analysis. The objective was to create an ML model that picks up the necessary information from textual data.

## Steps

### 1. Data Cleaning with NLTK

- Utilized the NLTK library for text data cleaning.
- Removed HTML tags, punctuation, numbers, and special characters.
- Eliminated short words and common stop words.

### 2. Tokenization and Stemming

- Performed tokenization on the cleaned text.
- Applied stemming to reduce words to their root form.

### 3. Feature Extraction using TF-IDF

- Used TF-IDF for feature extraction.
- Each word represented as a column with values from TF-IDF calculations.

### 4. Machine Learning Models with Hyperparameter Tuning

- Implemented Logistic Regression, SVM, and XGBoostClassifier.
- Conducted hyperparameter tuning for optimization.

### 5. Word Embeddings using Word2Vec

- Employed Word2Vec-google-news-300 for feature extraction.
- Combined feature vectors of each word by summation.

### 6. Bidirectional LSTM

- Implemented Bidirectional LSTM for capturing sequential information.

## Conclusion

The project involved a comprehensive exploration of data preprocessing techniques, feature extraction methods, and machine learning models for sentiment analysis. Different approaches provided insights into the effectiveness of each technique. The Bidirectional LSTM demonstrated the importance of capturing sequential information. Hyperparameter tuning optimized the models further. The project was a valuable learning experience to observe nuances in results produced by various techniques.

