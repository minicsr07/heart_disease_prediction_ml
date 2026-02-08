# Heart Disease Prediction using Machine Learning

## Overview
This project predicts the probability of heart disease using medical attributes. 
It was built as part of a Kaggle Playground Series competition and evaluated using ROC-AUC.

## Problem Type
- Binary Classification
- Target: Heart Disease (Presence / Absence)

## Dataset
The dataset used in this project is from the Kaggle Playground Series competition:

**Predicting Heart Disease (Season 6, Episode 2)**

Dataset link:  https://www.kaggle.com/competitions/playground-series-s6e2/data

Note: The dataset files (`train.csv`, `test.csv`) are not included in this repository due to Kaggle competition data usage restrictions.

## Models Implemented
- Logistic Regression (Baseline)
- Random Forest Classifier
- XGBoost Classifier (Final)

## Evaluation
- Metric: ROC-AUC
- Stratified 5-Fold CV ROC-AUC: **~0.955**

## Feature Importance
Top contributing features:
- Maximum Heart Rate
- Cholesterol
- ST Depression
- Chest Pain Type

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib

## How to Run
```bash
pip install -r requirements.txt
