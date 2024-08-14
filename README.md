# AI-Powered Credit Risk Classification

## Overview of the Analysis

The objective of this project is to assess the performance of a logistic regression model in predicting loan risk. The dataset comprises historical lending activity from a peer-to-peer lending platform, used to develop a model for evaluating borrower creditworthiness. The dataset includes financial variables such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status. In this context, the target variable is loan status, where a value of 0 indicates a healthy loan and a value of 1 signifies a high risk of default. The project is divided into two main tasks: first, splitting the data into training and testing sets; and second, constructing and training a logistic regression model on the training data (X_train and y_train). Subsequently, predictions were generated for the testing data (X_test), saved, and the model's performance was evaluated by generating a confusion matrix and printing the classification report.

## Results

**Machine Learning Linear Regression Model (99% Accuracy)**

* Class 0 (Healthy Loans)
    * Precision is 1.00, meaning all predicted class 0 instances are correct
    * Recall is 0.99, meaning 99% of actual class 0 instances were correctly predicted.
   
* Class 1 (High-Risk Loans)
    * Precision is 0.84, indicating that 84% of predicted class 1 instances are correct
    * Recall is 0.94, meaning 94% of actual class 1 instances were correctly predicted

## Summary

The high accuracy and weighted averages suggest that the model performs well overall, particularly in classifying the healthy loan label (class 0). The lower precision for high-risk loan labels (class 1), compared to class 0, indicates that while the model is good at identifying high-risk loan instances, it may have more false positives for this class. This insight can help guide further improvements to the model, especially when balance between classes is crucial for evaluating loan risk.
