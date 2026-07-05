# 🏡 House Prices Prediction using XGBoost
# 📌 Project Overview

This project predicts residential house prices using machine learning on the Kaggle House Prices dataset. The complete workflow includes data preprocessing, feature engineering, categorical encoding, model training, and submission generation.

# 🎯 Objective

Predict the final sale price of houses using property-related features such as lot size, neighborhood, quality, basement area, garage, and more.

# 📊 Dataset
Training Samples: 1460
Testing Samples: 1459
Features: 79

Dataset Source:

Kaggle House Prices Competition
🔧 Data Preprocessing

✔ Missing Value Handling

✔ Outlier Capping (IQR Method)

✔ Skewness Detection

✔ Log Transformation (log1p)

✔ One-Hot Encoding

✔ Feature Selection

# 🤖 Model Used
XGBoost Regressor

Hyperparameters:

XGBRegressor(
    n_estimators=1000,
    learning_rate=0.05,
    max_depth=3,
    random_state=42
)
# 📈 Results
Metric	Value
Kaggle Public Leaderboard Score	0.13021
Public Rank	2220
# 📚 Libraries
Python
NumPy
Pandas
Matplotlib
Scikit-learn
XGBoost
# 🚀 Project Workflow
Load Dataset
      ↓
Data Cleaning
      ↓
Missing Value Handling
      ↓
Outlier Capping
      ↓
Skewness Correction
      ↓
One-Hot Encoding
      ↓
Model Training (XGBoost)
      ↓
Prediction
      ↓
Kaggle Submission
# 📌 Future Improvements
Hyperparameter Tuning
Feature Engineering
Cross Validation
LightGBM Comparison
CatBoost Comparison
Model Ensembling
