Heart Disease Prediction using Logistic Regression

A machine learning classification project that predicts the presence of heart disease from clinical features using Logistic Regression.

📌 Overview

The objective of this project is to build a binary classification model that learns relationships between patient-related clinical measurements and the target heart-disease label.

🔄 Workflow
Heart Disease Dataset
        ↓
Data Loading
        ↓
Data Inspection
        ↓
Missing Value Analysis
        ↓
Descriptive Statistics
        ↓
Target Distribution Analysis
        ↓
Feature / Target Separation
        ↓
Stratified Train-Test Split
        ↓
Logistic Regression
        ↓
Prediction
        ↓
Accuracy Evaluation
🧹 Data Analysis

The notebook performs:

Dataset loading using Pandas
Shape inspection
Data type inspection
Missing-value checking
Descriptive statistics
Target-class distribution analysis
🧪 Train-Test Split

The dataset is divided into:

80% training data
20% testing data

A stratified split is used to preserve the target-class distribution between the training and testing sets.

🤖 Machine Learning Model

The project uses:

Logistic Regression

Logistic Regression is used as a binary classification model to estimate the probability of the target classes.

📏 Evaluation

Model performance is evaluated using:

Training accuracy
Test accuracy
🔮 Prediction

The notebook also demonstrates how a new patient's feature values can be supplied to the trained model to obtain a prediction.

🛠️ Technologies
Python
NumPy
Pandas
Scikit-learn
Logistic Regression
Train/Test Split
Accuracy Score
🎯 Learning Outcomes
Healthcare dataset analysis
Binary classification
Feature/target separation
Stratified train-test splitting
Logistic Regression
Model evaluation
Prediction on new observations
