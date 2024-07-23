# Sentiment_Analysis

# Sentiment Analysis on Amazon Reviews

## Project Overview

This project aims to perform sentiment analysis on Amazon reviews using various machine learning algorithms. The objective is to classify the reviews into positive and negative sentiments.

## Data

The dataset used for this project is Amazon reviews, which includes the text of the reviews and their corresponding sentiments.

Amazon reviews. (2021, May 15). Kaggle. https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews?select=train.csv  

## Models Used

1. **Naive Bayes**
2. **Logistic Regression**

## Results

- **Naive Bayes Accuracy**: 0.83
- **Logistic Regression Accuracy**: 0.85

## Detailed Explanation

## Data Preprocessing

1. Handling missing values by dropping rows with null reviews or sentiments.
2. Tokenizing and padding the text data for model input.

## Models
**Naive Bayes** 
Used for initial experiments.
Achieved an accuracy of 0.83.

**Logistic Regression**
Applied with feature scaling and optimization.
Achieved an accuracy of 0.85.

## Model Evaluation
Both models were evaluated using accuracy and classification reports. Logistic Regression outperformed Naive Bayes in terms of accuracy.

## Future Work
--> Experiment with more advanced models like LSTM and Transformers.
--> Fine-tune hyperparameters for better performance.
--> Utilize a larger dataset for more comprehensive training.
