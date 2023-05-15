# Credit Risk Classification Report

## Overview of the Analysis

The purpose of this analysis is to use machine learning to predict credit risk. The data used in this analysis is from a peer-to-peer lending services company. The data includes a variety of information about the loans, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The data also includes whether the loan was paid off or defaulted. The goal of this analysis is to use machine learning to predict whether a loan will be paid off or defaulted.

The machine learning process used in this analysis includes the following steps:

1. Preprocessing the data
2. Splitting the data into training and testing sets using the `train_test_split` method
3. Using the `LogisticRegression` algorithm to create a logistic regression classifier
4. Using the `RandomOverSampler` module to resample the training data
5. Evaluating the performance of the machine learning models

## Results

### Machine Learning Model 1: Logistic Regression with Original Data

* Accuracy Score: 0.9520479254722232
* Precision Score: 0.99
* Recall Score: 0.94

### Machine Learning Model 2: Logistic Regression with Resampled Data

* Accuracy Score: 0.9936781215845847
* Precision Score: 0.99
* Recall Score: 0.99

## Summary

Both models performed well, with the resampled data model performing slightly better overall. The resampled data model had a higher accuracy score, precision score, and recall score. The resampled data model also had a higher F1 score, which is a measure of a test's accuracy.

In both cases the accuracy of identifying high risk loans was lower than the accuracy of identifying low risk loans. This is likely due to the fact that there are fewer high risk loans in the data set. The resampled data model had a higher accuracy of identifying high risk loans than the original data model, but the accuracy of identifying low risk loans was the same for both models.

Based on the results of this analysis, I would recommend using the resampled data model. Though the accuracy of identifying low risk loans was the same for both models, the resampled data model had a higher accuracy of identifying high risk loans. This is important because the goal of this analysis is to identify high risk loans.
