# Credit Risk Classification
module 20 repo challenge

<p align="center">
<img src="Images/credit_pic.jpg" alt="crypto graphic" width="500" height="300"  >
</p>
  
---
## Table of Contents

- [Background](#background)
- [Part 1: Challenge Layout](#layout)
- [Part 2: Results/Report](#result)
- [Part 3: Conclusion](#conclusion)

---
## Background <a name="background"></a>

In this Challenge, I use various techniques to train and evaluate a model based on loan risk. I use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

---
## Part 1: Challenge Layout <a name="layout"></a>

1. Split the Data into Training and Testing Sets
2. Create a Logistic Regression Model with the Original Data
3. Write a Credit Risk Analysis Report

## Part 2: Results/Report <a name="result"></a>

1. Confusion Matrix
   
<p align="center">
<img src="Images/confusion_mat.png" alt="confusion_mat" width="300" height="150"  >
</p>

2.  Classification Report
   
<p align="center">
<img src="Images/classification_report.png" alt="classification_report" width="600" height="300"  >
</p> 

---
## Part 3: Conclusion <a name="conclusion"></a>   
How well does the logistic regression model predict both the `0` (healthy loan) and `1` (high-risk loan) labels?
 The logistical regression model predicts the heathy low risk loan with 100% percision, indicating that all positive predictions for class 0 are correct. The high risk loan is predicted with less percision at 87%, still reasonably precise in predicting class 1 instances. The accuracy of the model is 99%. The macro and weighted average metrics indicate that the model performs well across both classes, taking into account class imbalance.

