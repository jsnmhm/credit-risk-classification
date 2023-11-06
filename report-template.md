# Module 12 Report Template

## Overview of the Analysis

This analysis was conducted to create a model for predicting the health of a loan. Historical data consisting of loan size, interest rate, borrower income, total debt, debt to income ratio, number of accounts and derogatory marks was used to train a logistic regression model. This was used to classify the loan as either 0 (healthy) or 1 (high risk). The data was also resampled using RandomOverSampler to balance the classes in the training data.

## Results

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Balanced Accuracy Score: 0.95
  * Precision:
      * Healthy Loan: 1.00
      * High Risk Loan: 0.85
  * Recall:
      * Healthly Loan: 0.99
      * High Risk Loan: 0.91



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Balanced Accuracy Score: 0.99
  * Precision:
      * Healthy Loan: 1.00
      * High Risk Loan: 0.84
  * Recall:
      * Healthly Loan: 0.99
      * High Risk Loan: 0.99

## Summary

Both models do a good job predicting healthy loans, each with a high precision and recall score. High-risk loans are slightly less precisely classified, with Model 1 having a precision of 0.85 compared to Model 2's 0.84.  Model 2 is significantly better than Model 1 in terms of recall for high-risk loans (0.99 vs. 0.91). 

Considering the cost of accurate loan risk prediction, the superior balanced accuracy score of 0.99 and the substantially higher recall for high-risk loans make Model 2 the better option.
