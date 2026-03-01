# Heart_Diesee_Pre-
Heart Disease Prediction using Machine Learning with EDA, preprocessing, and model comparison. An end-to-end ML project to predict the presence of heart disease based on medical attributes.


📌 Project Overview

This project aims to predict whether a patient has heart disease using various medical attributes. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

Early prediction of heart disease can help in preventive healthcare and better treatment planning.

🎯 Objectives

Perform comprehensive Exploratory Data Analysis (EDA)

Handle missing values and data inconsistencies

Encode categorical variables

Scale numerical features

Train multiple classification models

Compare models and select the best performer

📂 Dataset Information

File: kedar.xls

Notebook: Heart_Diesease_Pre.ipynb

Dataset contains medical attributes such as:

Age

Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol

Fasting Blood Sugar

ECG Results

Maximum Heart Rate

Exercise Induced Angina

ST Depression

Target (Heart Disease: Yes/No)

🔎 Exploratory Data Analysis (EDA)

Analysis performed:

Target variable distribution

Correlation heatmap

Age vs Heart Disease

Cholesterol & BP analysis

Outlier detection using IQR

Feature relationship visualization

📊 Key Insights:

Chest pain type and maximum heart rate strongly influence prediction.

Cholesterol and resting BP show moderate correlation.

Certain features have higher predictive importance.

⚙️ Data Preprocessing

Handling missing values

Label Encoding / Ordinal Encoding

Feature Scaling (StandardScaler / MinMaxScaler)

Train-Test Split

🤖 Machine Learning Models Implemented

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

XGBoost (if implemented)

📈 Model Evaluation Metrics

Accuracy Score

Precision

Recall

F1 Score

Confusion Matrix

Cross Validation

Hyperparameter Tuning (GridSearchCV)

🏆 Best Model

After comparing models:

Random Forest / XGBoost achieved the highest accuracy.

Ensemble methods performed better due to handling non-linear medical feature relationships.

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

Jupyter Notebook
