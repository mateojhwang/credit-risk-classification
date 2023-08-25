# Module 12 Report Template

The purpose of creating a logistic regression model is to determine whether a loan is considered safe or high-risk when given out to a borrower. In order to determine this, fitted the model based on loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, total debts, and loan status. The dataset contained 75036 healthy loans and 2500 high-risk loans.
The first step of the machine learning process was to split the data between loan status and everything else. I then created the first logistical regression model to apply to the testing data. After getting the accuracy scores, confusion matrix and score, I started to create the second logistic regression model. This time I used a RandomOverSampler to make sure there was an equal number of data points. After getting these results I compared them to first model.

## Results

Machine Learning Model 1:

Accuracy: 99.2%
Precision of Healthy: 100% 
Precision of High-risk: 87%
Recall of Healthy: 100%
Recall of High-risk: 89%

Machine Learning Model 2:

Accuracy: 99.52%
Precision of Healthy: 100% 
Precision of High-risk: 87%
Recall of Healthy: 100%
Recall of High-risk: 100%

## Summary

The second model with Reza moles data seems to perform better as it has a better weighted precision and more accurrately classifies high-risk loans.It is more important to predict the 1’s or high risk loans because there is more on the line. Not classifying a high-risk loan correctly can lead to more problems than misclassifying a healthy loan.
