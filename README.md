# ⚡ Electricity Consumption Prediction

A machine learning pipeline to predict electricity consumption using various regression models, stacked ensembles, and feature importance analysis. The pipeline includes extensive preprocessing, hyperparameter tuning, model evaluation, and interpretability using SHAP values.

---

## 🔍 Overview

This project builds and evaluates a set of regression models to forecast electricity usage, leveraging different sets of features. It also applies stacking techniques to improve predictive performance, and evaluates feature importance using SHAP.

---

## 📂 Project Structure
```
.
├── energy_consumption_prediction.ipynb       # Main notebook
├── data_extraction.ipynb                     # Notebook for merging datasets 
├── data/                                     # Raw and processed datasets
├── doc/									  # Supporting documents
├── test/									  # Folder for codes under testing
└── README.md
```

---

## 🚀 Features

- Preprocessing pipeline with safe pre- and post-split transformations
- GridSearchCV-based hyperparameter tuning for multiple regressors
- Stacking ensemble using the best-performing models
- Performance metrics: MAE, RMSE, R², Adjusted R²
- Feature importance analysis

---

## 🧪 Models Used

- Linear Regression
- ElasticNet
- Support Vector Regression (SVR)
- Decision Tree
- Random Forest
- AdaBoost
- XGBoost
- Stacking Regressor (custom ensemble)
- Neural Network
- Time Series Analysis

---