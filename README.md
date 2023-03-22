## Overview of the Analysis

In this challenge, I used SciKitLearn functions to manipulate the original data into separate training and testing data sets to evaluate a loan risk model. The data set used contains historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

-I began the analysis by training a model to detect the risk factor of loans. The purpose is to determine wether a loan is considered healthy or high-risk.

-The data provided financial information including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory mark count, total debt and loan status. 

-The goal was to predict the loan status using the remaining given features

-I split the data into training and testing datasets, and used the value_counts function to check the balance of the target values of loan status. I trained the model using the train_test_learn module using my assigned train and test variables. 

-I used the LogisitionRegression module to build a Logisitc Regression model that would be fit to predict loan status. I then built a confusion_matrix and classification report that revealed and accuracy score of 99%.

-I used machine learning to generate the precision and recall of the test data. Precision calculates out of all classified high-risk loans, how many were actually high risk, and the same for healthy loans. Recall calculates how well the model correctly classified the loan risk. 

## Results

Machine Learning Model: 

-Precision: 100% accuracy in Healthy Loans and 87% accuracy for High-Risk Loans

-Recall: 100% accuracy in Healthy Loans and 89% accuracy for High-Risk Loans

-F1-score: 100% accuracy in Healthy Loans and 88% accuracy for High-Risk Loans

## Summary

I believe this model is useful to identify healthy loans as it performed at 100% accuracy. I believe further testing would need to be done on what the model labels high-risk loans as the given precision and recall leaves just over 10% of false positives and negatives. The scores are a good indicator of healthy loans and loans that should be flagged for further investigation. 
