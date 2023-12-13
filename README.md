# Quora Text Classification

This repository contains code for text classification on the Quora Insincere Questions Classification dataset. The main focus is on using the bag-of-words model for text representation and logistic regression for classification.

## Data Download and Exploration

The initial steps involve downloading the dataset from Kaggle using the `opendatasets` library and exploring the data using Pandas. The dataset includes labeled examples of sincere and insincere questions.

## Text Preprocessing Techniques

The notebook covers various text preprocessing techniques, including tokenization, stop word removal, and stemming. These techniques are essential for converting raw text into a format suitable for machine learning models.

## Bag of Words Model Implementation

The bag-of-words model is implemented using the scikit-learn library's `CountVectorizer`. The process involves creating a vocabulary and transforming text documents into vectors of word counts. Various parameters of the `CountVectorizer` are configured, such as tokenization, lowercase conversion, and the exclusion of stop words.

## Machine Learning Models for Text Classification

The notebook demonstrates the use of logistic regression for text classification. It includes the following steps:

1. Splitting the dataset into training and validation sets.
2. Training a logistic regression model on the training set.
3. Evaluating the model on both the training and validation sets using accuracy and F1 score.

The trained model is then used to make predictions on the test set, and the results are saved in a submission file (`submission.csv`) for Kaggle.

## Kaggle Submission

The final section of the notebook involves making predictions on the test set and preparing a submission file for Kaggle. The `submission.csv` file is generated, containing the model's predictions for the provided test questions.

Feel free to use this code as a starting point for text classification tasks or as a reference for working with the Quora Insincere Questions Classification dataset.
