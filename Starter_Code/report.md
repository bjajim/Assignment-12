# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
To predict accuracy between original data and sampled data by estimating probabilities using a logistic regression equation and forecasting after classification. This type of analysis helps predict the likelihood of a choice being made.

* Explain what financial information the data was on, and what you needed to predict.
Financial information is on variables such as loan size, interest rate, borrower's income, number of accounts, derogratory remarks and total debts.

Needed to predict Loan Status

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
In the loan status there are 75,036 healthy loans and 2500 High Risk loans

* Describe the stages of the machine learning process you went through as part of this analysis.
Spliting of Data to 2 Data Sets: 'Testing' and 'Training', Created a Logistic Regression Model with Original Data, Evaluated Model Performance with Original Data, Resampled the Data and Predicted Logistic Regression with resampled Training Data 

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
Loggistic Regression is a statistical model formed from a logistic functionto model a binary dependent variables. It is used to solve classification problems which is basicaly trying to predict between a number of value example True or False 

Re-Sampling method is a method use in Machine Learning on Data that seems imbalance it is used to fill up the imbalance side of the data so that each possible outcome has the same number of observations with the others. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
*Accuracy: 95% 
*Precision: 0.99
*Recall Scores: 0.99


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
*Accuracy: 99%
*Precision: 0.99
*Recall Scores: 0.99

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
Machine Learning model 2 seems to perform best because of 99% Accuracy 

* Does performance depend on the problem we are trying to solve? YES (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
It's more important to predict the 1s

If you do not recommend any of the models, please justify your reasoning.
