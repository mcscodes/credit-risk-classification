# credit-risk-classification

"In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers."

## Overview of the Analysis

The purpose of this analysis was to build and evaluate a machine learning model to predict the loan status of borrowers. The model's objective is to determine whether a loan will be repaid (loan_status = 0) or not (loan_status = 1), based on several borrower attributes, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The predictions from this model can help the company make informed decisions about lending practices, reducing risk and improving overall financial outcomes.

## Results

The logistic regression model was used for this analysis. Below are the performance metrics of the model:

* Accuracy Score: 99%
* Precision Score:
- Class 0 (Loan repaid): 100%
- Class 1 (Loan defaulted): 85%
* Recall Score:
- Class 0 (Loan repaid): 99%
- Class 1 (Loan defaulted): 91%
* F1-Score:
- Class 0 (Loan repaid): 100%
- Class 1 (Loan defaulted): 88%

## Summary

The logistic regression model demonstrates strong performance, with an overall accuracy of 99%, which is a high indicator of the model's effectiveness. The precision and recall scores for predicting whether a loan will be repaid (Class 0) are excellent, at 100% and 99%, respectively. This means the model is highly effective at identifying loans that will be repaid, with very few false positives.

For predicting loan defaults (Class 1), the model shows a good precision score of 85% and a strong recall score of 91%. This indicates that while the model is generally effective at identifying loans that will default, there is still a slight risk of false positives, where the model might incorrectly predict a default.

Based on these results, I recommend the use of this logistic regression model for loan status prediction. The model's high accuracy, precision, and recall scores indicate that it is reliable for identifying both loans that will be repaid and those that are at risk of defaulting. The model better (almost perfectly) predicts healthy loans. The model is only able to predict high risk loans 85% of the time. Further tuning or additional models could be explored to improve the precision for predicting defaults, thereby minimizing potential financial risks for the company.





Summary


