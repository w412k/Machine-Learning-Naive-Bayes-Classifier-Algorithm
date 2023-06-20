# Machine Learning Naive Bayes Classifier Algorithm

This repository contains a practice exercise for implementing the Naive Bayes Classifier Algorithm to predict the class of wine based on certain inputs. The dataset used for this exercise is the wine dataset available in the scikit-learn library.

## Naive Bayes Classifier

Naive Bayes is a probabilistic machine learning algorithm based on Bayes' theorem. It assumes that the presence of a particular feature in a class is independent of the presence of other features. This assumption simplifies the computation and allows for efficient training and prediction. Naive Bayes classifiers are commonly used for text classification, spam filtering, sentiment analysis, and recommendation systems.

There are different types of Naive Bayes classifiers, including Multinomial Naive Bayes and Gaussian Naive Bayes. In this exercise, we will train models using both of these classifiers and compare their performance.

## Dataset

The wine dataset used in this exercise contains a collection of attributes (e.g., alcohol content, acidity) for different wines, along with their respective classes. It is a popular dataset for practicing classification algorithms.

## Implementation

The implementation in this repository involves the following steps:

1. Loading the wine dataset using scikit-learn.
2. Splitting the dataset into training and testing sets.
3. Training a Multinomial Naive Bayes model using `MultinomialNB` from scikit-learn.
4. Training a Gaussian Naive Bayes model using `GaussianNB` from scikit-learn.
5. Evaluating the performance of the models by generating a confusion matrix.

## Results

The generated confusion matrix will help identify where the models make errors in predicting the wine classes. By analyzing the results, you can gain insights into the strengths and weaknesses of the Naive Bayes classifiers for this particular dataset.



