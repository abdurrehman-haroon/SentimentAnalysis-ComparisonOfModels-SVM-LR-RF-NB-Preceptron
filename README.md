# Sentiment Analysis Project Overview

This project aims to perform sentiment analysis on textual data using various machine learning techniques. Sentiment analysis, also known as opinion mining, involves analyzing text to determine the sentiment expressed, In this project there were four sentiments negative, positive, neutral and not_relevant. The data was scraped from twitter, it primarly focused on apples new products.

## Objective

The primary objective of this project is to develop a sentiment analysis system capable of accurately classifying the sentiment conveyed in textual data. By leveraging machine learning algorithms and natural language processing (NLP) techniques, the project aims to build models that can automatically discern the sentiment of text.

## Components

### 1. Preprocessing and Cleaning

The preprocessing and cleaning phase involves preparing the text data for analysis. This includes tasks such as:

- Removing URLs
- Converting text to lowercase
- Removing non-alphabetic characters
- Removing stop words
- Stemming + lemmatization to reduce words to their base form

### 2. Feature Extraction

Feature extraction transforms the preprocessed text data into numerical features suitable for machine learning algorithms. This project employs and compares various techniques such as:

- CountVectorizer: Converts text documents into a matrix of token counts.
- TfidfVectorizer: Converts text documents into a matrix of TF-IDF features.
- N-gram Vectorization: Captures sequences of adjacent words as features.

### 3. Model Training

In the model training phase, multiple classification algorithms are trained on the extracted features. The models used in this project include:

- Naïve Bayes
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- Perceptron

Evaluation metrics such as accuracy, precision, recall, and F1 score are computed to assess the performance of each model.

### 4. Comparing Models

The performance of the trained models is compared using visualizations to understand their strengths and weaknesses. Bar plots are generated to compare accuracy, precision, recall, and F1 score for each model using both micro and macro averaging.

## Dataset

The dataset used in this project is located at `data/Sentiment Analysis Dataset.csv`. It contains a collection of text data along with corresponding sentiment labels, which serve as the ground truth for training and evaluating the models.
