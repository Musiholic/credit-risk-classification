# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the analysis was to determine the accuracy of our classification model to predict high-risk/low-risk loans.
* The financial data contained loan data including negative marks associated with the loan, and the goal was to predict high-risk/low-risk loans to assist in determining credit worthiness of borrowers.
* Variables used to predict credit worthiness were things such as loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt.
* After calling in the data, and creating label sets from loan_status and using the remaining features as our x columns.
* This assignment was using logistic regression to determine the credit worthiness of borrowers. This is because logistic regression models are great for binary problems (yes/no, credit worthy/unworthy, win/lose).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
* Model 1 showed the following:
* 0: 100% precision, .99 recall, 100% f1-score
* 1: 85%, .91 recall, 88% f1-score
* accuracy: 99% (macro avg: 92%, weighted avg: 99%)

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

* Logistic regression is a great model for classification problems where the outcome being predicted is binary
* In this case, it's definitely important that borrowers without credit worthiness are more accuratly predicted so that bad loans aren't being given