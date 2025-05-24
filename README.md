# Rainfall-Prediction-using-Machine-Learning
# Overview
This project leverages machine learning techniques to predict rainfall occurrence based on meteorological parameters. Using classification models, we aim to provide accurate predictions that can assist in agriculture, disaster management, and urban planning.

# Dataset
The dataset consists of 366 records with 12 features, including:

Pressure

Temperature (max, min, and average)

Dew point

Humidity

Cloud cover

Sunshine duration

Wind direction and speed

Rainfall occurrence (Yes/No)

# Project Pipeline
Data Preprocessing

Handling missing values

Feature cleaning and selection

Data scaling & balancing

Exploratory Data Analysis (EDA)

Statistical insights & feature correlations

Outlier detection & distribution visualization

# Model Training

Implementing Logistic Regression and SVC

Performance evaluation using ROC-AUC Score and Confusion Matrix

# Result
The Logistic Regression model outperformed SVC in rainfall prediction. It achieved a test ROC AUC score of 95.75% and test accuracy of 91%, demonstrating strong classification ability and generalization. SVC, with a test ROC AUC of 94% and accuracy of 82%, showed signs of overfitting. These findings highlight the effectiveness of Logistic Regression in handling class imbalance and producing reliable predictions.
