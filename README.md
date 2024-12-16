# credit-risk-classification
Module 20 Challenge - Credit Risk Classification

For this project, I used supervised machine learning to train and evaluate a model based on loan risk data.

# Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

# Results

The accuracy of predicting a healthy loan (0) is 100%.  The accuracy of predicting a high-risk loan is 91%.  So the model does a better job of predicting a healthy loan than it does predicting a high-risk loan.


# Credit Analysis Report:
*Purpose:*
The purpose of this analysis is to model the provided data using a supervised logistic regression model.  The goal is to make predictions on whether a given customer represents a healthy or high-risk loan prospect.

*Model Overview:*
Per the numbers in cell #33
Model Accuracy:  0.99 (99%)
Precision of predicting Healthy Loan (0): 1.00
Recall of predicting Healthy Loan (0):  1.00
Precision of predicting High-Risk Loan (1):  0.87
Recall of predicting High-Risk Loan (1):  0.95

*Summary:*
I would recommend this model for use by the company for predicting whether a given customer is a good loan risk.  The model does an excellent job of predicting (100%) whether a customer represents a good loan risk.  The model does a slightly worse job of predicting (91%) whether a customer represents a high-risk loan risk.  Given that the model still does an excellent job of detecting the true positives for high-risk loans (with a Recall value of 95%), I believe that this would be an effective model overall.