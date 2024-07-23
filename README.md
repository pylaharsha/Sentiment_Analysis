# Sentiment_Analysis

# Sentiment Analysis on Amazon Reviews

## Project Overview

The primary objective of this project is to perform sentiment analysis on Amazon product reviews to classify them into positive and negative sentiments. Sentiment analysis is a common task in Natural Language Processing (NLP) used to understand the emotional tone behind a body of text. This project explores different machine learning models to achieve accurate sentiment classification. 

## Data

The dataset used for this project is Amazon reviews, which includes the text of the reviews and their corresponding sentiments.

Amazon reviews. (2021, May 15). Kaggle. https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews?select=train.csv  


## Model Selection and Training

**Naive Bayes**: A probabilistic classifier based on Bayes' theorem, suitable for text classification tasks.
**Logistic Regression**: A linear model for binary classification that predicts the probability of a binary response.

## Model Evaluation

1. Evaluating the performance of each model using metrics such as accuracy, precision, recall, and F1-score.
2. Comparing the results of different models to determine the best-performing model for this task.

## Data Preprocessing

1. Handling missing values by dropping rows with null reviews or sentiments.
2. Tokenizing and padding the text data to convert it into numerical format suitable for machine learning models.

## Results

The performance of the models is as follows:

**Naive Bayes**: Achieved an accuracy of 0.83 on the test dataset.
**Logistic Regression**: Achieved an accuracy of 0.85 on the test dataset.

## Conclusion

The Logistic Regression model outperformed the Naive Bayes model in terms of accuracy. This indicates that Logistic Regression is more effective for this particular sentiment analysis task on Amazon reviews. Future work includes experimenting with more advanced models like LSTM and Transformers, fine-tuning hyperparameters, and utilizing a larger dataset for more comprehensive training.

## Future Work
1. Experiment with more advanced models like LSTM and Transformers.
2. Fine-tune hyperparameters for better performance.
3. Utilize a larger dataset for more comprehensive training.
