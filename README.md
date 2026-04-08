# 🌍 Earthquake Magnitude Classification System

## 📌 Overview
This project focuses on predicting earthquake magnitude categories using machine learning techniques on real-world seismic data. 
The goal is to improve classification accuracy and robustness by addressing class imbalance and leveraging ensemble learning.


## Problem
Earthquake datasets are often highly imbalanced and noisy, leading to poor prediction performance in traditional machine learning models. 
Standard approaches struggle to accurately classify magnitudes, especially for less frequent earthquake categories.

## Solution
This project addresses the problem by applying SMOTE to handle class imbalance and using ensemble learning techniques (Stacking and Voting) to improve prediction robustness.
Combined with feature engineering and hyperparameter tuning, the system significantly enhances classification accuracy and reliability.

## 🚀 Features
- End-to-end machine learning pipeline
- Data preprocessing and feature engineering
- Handling class imbalance using SMOTE
- Model optimization using hyperparameter tuning
- Ensemble models (Stacking, Voting)

---

## 🧠 Models Used
- Logistic Regression
- SVM
- Random Forest
- Gradient Boosting
- XGBoost
- Ensemble Models (Voting, Stacking)

---

## 📊 Results
- Achieved **92.5% accuracy (Stacking Ensemble)**
- Achieved **93% accuracy with SMOTE + Tuned XGBoost**
- Improved performance over baseline models

---

## 🛠️ Tech Stack
- Python
- Scikit-learn
- Pandas, NumPy
- XGBoost
- Matplotlib / Seaborn
