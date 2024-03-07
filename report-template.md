# Module 12 Report Template

## Overview of the Analysis

The analysis presented studies a dataset that pertains to an individual's credit score with the following parameters:
* Loan Size
* Interest Rate
* Borrower Income
* Debt to Income
* Number of Accounts
* Derogatory Marks
* Total Debt

Using these parameters, it can be ascertained whether or not an individual is a high-risk loan recipient or not. 
The dataset is then split between its features (X) and the loan status (y) between train and test datasets to train the model. 

The model used in this analysis is a Logistic Regression model, wherein the curve of the data follows a trend that limits itself to its maximum and minimum values.

To ascertain whether or not this model was the correct choice, after making predictions, a confusion matrix and a classification report would be created to find out the precision and other scores.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Logistic Regression Model:
    * Score = 0 (Healthy Loan)
        * Precision = 1.00
        * Recall = 1.00
        * f1-score = 1.00
    * Score = 1 (High-Risk Loan)
        * Precision = 0.87
        * Recall = 0.95
        * f1-score = 0.91
    * Overall Accuracy = 0.99

## Summary

The Logistic Regression model is a very good model to predict the loan status of this format of dataset for credit score. It is precise and reliable, especially for predicting healthy loans. Please be sure to confirm the features are similar when testing a different dataset.
