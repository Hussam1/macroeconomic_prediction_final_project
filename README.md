# Telecom customer's churn using machine learning


## Summary

**Motivation:** As part of my data science bootcamps projects, we intent to perform "customer churn modeling" for company within the telecom industry
<br />
<br />**Goal:** The goal is to test and train multiple machine learning models in order to select the one with most valid business case
<br />
<br />**Business Case:** The company will be using this model to predict customers at risk of churning. hypothetical case was:
<br />1- The contract's life time value is 1000$
<br />2- Customers at risk of churning will be called and offered 10% discount if they maintain/continue their contract
<br />3- based on the model results, what is the net effect on the company's income statement
<br />
<br />**Next Steps:** 
<br />- Test if customer's location has any impact on customer's behaviour
<br />- Test if manipulating correlated features will have impact on customer's behaviour and subsequently churning rate
<br />- Expand more on hyperparameter tuning
<br />- Expand more on feature importance and selection
<br />![img!](img/feature_importance.jpg)


## Introduction
The approach was as following

![img!](img/approach.JPG)



## Models tested
The following Machine learning models were tested:

<br />- Logistic Regression
<br />- SVM
<br />- KNN
<br />- RandomForest
<br />- AdaBoost
<br />- Gradient Boost
<br />- Decision Tree
<br />- XGBoost
<br />- PyCaret classification module



## Model chosen:

Logistic Regression with the following results:

![img!](img/confusion_matrix.jpg)
<br />![img!](img/classification_report.jpg)
<br />![img!](img/roc_curve.jpg)



## Business Case clarification:
![img!](img/business_case.JPG)


