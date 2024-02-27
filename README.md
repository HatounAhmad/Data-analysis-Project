# Sentiment Analysis of Twitter Users' Tweets about ChatGPT

## Goal and Problem:
Our project aimed to analyze the sentiments of Twitter users regarding ChatGPT by analyzing their tweets. The main challenge was to determine the overall sentiment expressed in these tweets. We focused on cleaning and preprocessing the data and then applied various machine learning methods to achieve accurate sentiment analysis.

## Dataset Description:
The dataset used in the analysis consisted of 217,622 tweets collected directly from Twitter users. The tweets were not preprocessed and were categorized into three sentiment categories: good, bad, and neutral.

## Data Preprocessing:

### Data Cleaning:
We cleaned the tweets by removing irrelevant information, converting text to lowercase, and mapping labels to integers to prepare them for sentiment analysis.

### Data Balance:
We observed an imbalance in the distribution of labels. To address this issue, we implemented the SMOTE model to rebalance the dataset.

## ML Methods:
Initially, we used Naive Bayes and Logistic Regression methods. After thorough evaluation, we selected the following methods:

- Naive Bayes
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- k-Nearest Neighbors (k-NN)

## Results:
Among the models, Naive Bayes, Logistic Regression, and Decision Tree performed well in terms of accuracy. The Logistic Regression model achieved an accuracy rate of 0.73, the Naive Bayes model achieved 0.70, and the Decision Tree model achieved 0.62. However, further optimization is required for the Random Forest, Support Vector Machine (SVM), and k-Nearest Neighbors (k-NN) models.

## Conclusion:
In conclusion, our project successfully analyzed the sentiments of Twitter users regarding ChatGPT. We cleaned and balanced the dataset, applied various machine learning methods, and achieved accurate sentiment analysis. The top-performing models were Logistic Regression, Naive Bayes, and Decision Tree. We also identified areas for improvement in the Random Forest, SVM, and k-NN models.
