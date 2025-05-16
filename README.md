# ⚡ Energy Consumption Analysis

A machine learning pipeline to predict energy consumption using various regression models, stacked ensembles, and feature importance analysis. The pipeline includes extensive preprocessing, hyperparameter tuning, model evaluation, and interpretability.

---

## 🔍 Overview

This project builds and evaluates a set of regression models to forecast energy usage, leveraging different sets of features. It also applies stacking techniques to improve predictive performance and evaluates feature importance.

🗓️ Project Period: March 31, 2025 – April 10, 2025

📊 Data Source: 
- Korea Electric Power Corporation: https://bigdata.kepco.co.kr/cmsmain.do?scode=S01&pcode=000171&redirect=Y
- Korea Meteorological Administration: https://data.kma.go.kr/data/grnd/selectAsosRltmList.do?pgmNo=36
- Korea Gas Corporation: https://www.data.go.kr/data/15049904/fileData.do?recommendDataYn=Y

---

## 📂 Project Structure
```
.
├── energy_consumption_prediction.ipynb  # Main notebook
├── data_extraction.ipynb                # Notebook for merging datasets 
├── data/                                # Raw and processed datasets
├── docs/                                # Supporting documents and presentations
├── test/                                # Folder for codes under testing
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
- Simple Neural Network Model
- SARIMAX

---

## 👥 Contributors

- [Jeong Gukho](https://github.com/GUKHOJeong/)
- [Jeong Woogun]()
- [Kim Hyungeun](https://github.com/hyungeunkk)
- [Kim Juneon]()
- [Kimm Soo Min](https://github.com/somnio-kimm)
