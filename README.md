# credit-risk-classification

## Overview of the Analysis

This analysis is for the purpose of using machine learning to predict the status of potential loans to be of high risk status or healthy for lending purposes by considering a variety of factors including:

* The size of the loan
* The interest rate
* The income, debt, and the debt to income rate of the borrower
* The number of accounts of the borrower
* The number of derogatory marks

By applying pre-labeled data into a Logistic regression, we hope to be able to make accurate predictions of high-risk status for new loan applications.

In order to use Logistic regression, the data was split into training data and testing data. The logistic regression model was trained on the training data and then used to predict high risk status on the unlabeled testing data. These predictions were then compared to the actual testing data labels to evaluate accuracy.

## Results

* Logistic regression results
    * Accuracy: 99%
    * Precision:
        * Healthy: 100%
        * High Risk: 85%
    * Recall
        * Healthy: 99%
        * High Risk: 95%

## Summary

Because this model is so effective at determining healthy loans but is less accurate in predicting high-risk loans, this model is best used for approving loans as healthy and merely flagging potentially high-risk loans that require further investigation rather than outright denying them. This model would probably best be used by loaners with highly conservative lending strategies that would prefer to avoid risk even at the cost of some potentially missed healthy investments.

## Considerations

This is my submission for Module 20 of the Data Visualization Bootcamp and exists for educational purposes. All code included is original and based on code provided in class material.