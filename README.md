# Diabetes-Prediction
Overview
This project focuses on predicting whether a patient has diabetes based on a variety of medical features. We utilize various machine learning classification models such as Random Forest Classifier, Extra Trees Classifier, XGBoost, K-Neighbors Classifier, Logistic Regression, Naive Bayes, and Support Vector Classifier (SVC) to build and evaluate the models.

The dataset used for this project is the PIMA Indians Diabetes Database, which contains health-related information such as glucose levels, BMI, age, etc. The goal is to classify patients as either having diabetes or not based on these features.

Dataset
The dataset used is the PIMA Indians Diabetes Database, available on Kaggle. It consists of the following features:

Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age
Outcome (Target variable: 0 = No Diabetes, 1 = Diabetes)
Models Used
Several machine learning models were implemented to classify whether a patient has diabetes:

Random Forest Classifier
Extra Trees Classifier
XGBoost
K-Neighbors Classifier
Logistic Regression
Naive Bayes
Support Vector Classifier (SVC)
Evaluation Metrics
The models were evaluated based on the following metrics:

Accuracy: The percentage of correct predictions.
Precision: The number of true positives divided by the total number of predicted positives.
Recall: The number of true positives divided by the total number of actual positives.
F1-Score: The harmonic mean of precision and recall.
Confusion Matrix: A table that shows the true vs. predicted classifications.
Results uploaded as a picture in the main file.

From the table above, Logistic Regression performed the best in terms of AUC and Precision


Conclusion
In this project, compared several machine learning models for predicting diabetes based on medical data. While Extra Trees Classifier outperformed the others in most metrics, other models such as Logistic Regression and Random Forest Classifier also showed competitive results. Future work could include hyperparameter tuning and feature selection to further improve model performance.
