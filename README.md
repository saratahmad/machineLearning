# Authorship Attribution

## Project Overview
In this project, we use the data generated using six Twitter users’ scraped tweets to make training and test datasets. Three machine learning models are used to train and test the data for Authorship Attribution.

## Feature Preparation
Data is split in an appropriate split ratio, and a collective vocabulary and a corresponding bag of word features are made. In addition to this, BERT Sentence Embeddings are used to get the features. The advantage of using this over features based on pure counts is the inclusion of context and semantic information, which means that the features code richer information and can therefore lead to models performing better given that they provide a higher quality input.

## KNN
1. Scikit Learn’s KNN model is used to get predictions for authorship attribution.
2. 5-fold cross-validation is performed.
3. Scikit-learn functions are used to report the accuracy, classification report including macro-average (precision, recall, and F1), and confusion_matrix function.

## NN
1. Scikit Learn’s NN model is used to get predictions for authorship attribution.
2. 5-fold cross-validation is performed.
3. Scikit-learn functions are used to report the accuracy, classification report including macro-average (precision, recall, and F1), and confusion_matrix function.

## Ensemble Methods
1. Used Random forests as Ensemble methods for training and prediction.
2. Scikit-learn functions are used to report the accuracy, classification report including macro-average (precision, recall, and F1), and confusion_matrix function.
