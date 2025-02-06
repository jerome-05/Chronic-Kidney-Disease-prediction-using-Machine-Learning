## CHRONIC KIDNEY DISEASE PREDICTION
A COMPARITIVE STUDY ON VARIOUS MACHINE LEARNING MODELS AND IMPUTATION TECHNIQUES
INTRODUCTION
Chronic Kidney Disease (CKD) is a progressive condition characterized by the gradual loss of kidney function. It is also associated with increased risk of cardiovascular disease and end – stage kidney disease. This project aims to diagnose the presence of CKD using various machine learning models such as Logistic Regression, Decision Tree, Random Forest and Linear Support Vector Machine. The project involves pre-processing the data, imputing missing values with techniques like KNN Imputation, Iterative Imputation and Mice Forest Imputation, encoding categorical variable and feature selection.

DATASET
The dataset used for this project is the Chronic Kidney Disease Dataset available from the UCI Machine Learning Repository. It contains 400 instances with 24 features, including blood pressure, blood glucose levels, and other indicators relevant to CKD diagnosis.

Source: https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease

IMPUTATION TECHNIQUES
1. KNN Imputation: KNN imputation involves finding the "k" nearest neighbours to a data point with missing values. The missing value is then imputed by averaging or interpolating the values of these nearest neighbours.

2.Iterative Imputation: The Iterative Imputation technique with a Random Forest Regressor as the estimator is a method used to fill missing values in a dataset by iteratively predicting and updating the missing values based on other features in the dataset.

3.MICE Forest Imputation: The Multiple Imputation by Chained Equations (MICE) algorithm is useful when the data has missing values in multiple variables. It starts by filling in missing values in each variable with some initial values like mean, median, or mode and then regresses it on the other variables. This process is repeated multiple times, generating multiple imputed datasets. The final imputed dataset is the combined result of those datasets.

MACHINE LEARNING MODELS
Logistic Regression
Decision Tree Classification
Random Forest Classification
Linear Support Vector Classification
RESULTS
Accuracy scores of each imputed dataset and machine learning models is given below: Description

Visual representation of accuracy of each imputed dataset and machine learning models is given below: Description
