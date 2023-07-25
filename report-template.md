# Module 12 Report 

## Overview of the Analysis

The purpose of the analysis is to evaluate the performance of a binary classification model on a given dataset. The analysis aims to assess how well the model can distinguish between two classes (class 0 and class 1) and make predictions based on the input features. The analysis involves several steps:
*Data Preparation, Model Training, Model Evaluation, Confusion Matrix, Classification Report, Purpose of Analysis

The financial information was on loan risk. The dataset used for analysis was a historical lending activity log from a peer to peer lending service company. The model was created to evaluate loan risk based on multiple peer features. Such as: loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks,	total debt.
Basic information about the variables you were trying to predict: the data set consisted of 75036 healthy loan (class 0), and 2500 high risk loans (class 1) based on the imbalance in classes the model was able to predit health loans (class 0) more precise than the high risk loans (class 1).  

We used a LogisticRegression method on the given data.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Logistic Regression Model scores:
 
  * Accuracy:  The accuracy is approximately 99%, indicating that the model is accurate in predicting both class 0 and class 1 samples.
  * Precision: For class 0, the precision is 1.00, indicating that all positive predictions for class 0 are correct. The model is very precise in predicting class 0 instances. For class 1, the precision is 0.87, meaning that about 87% of the positive predictions for class 1 are correct. The model is still reasonably precise in predicting class 1 instances.
  * Recall: For class 0, the recall is 1.00, indicating that the model correctly identifies all positive samples of class 0. It has a high ability to capture class 0 instances.For class 1, the recall is 0.89, meaning that the model captures about 89% of the actual positive samples of class 1. It has a reasonably good ability to identify class 1 instances.


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
  In this case it is more important to predict class 0 better because there is a imbalance in the dataset where we have a much lower amount of high risk loans to train the model. By predicting high risk loans better the model can predict class 1 (heathly loans) better by default.

