🛡️ Proactive Fraud Detection
------------------
📌 Overview

This project focuses on fraud detection in financial transactions using machine learning. It demonstrates the complete pipeline — from data cleaning and feature engineering to model building, evaluation, and prevention strategies.

The goal is to proactively identify fraudulent activities by combining domain-driven features with a robust XGBoost model while handling class imbalance using SMOTE.
------------------
🚀 Key Highlights

✅ Data Cleaning: Missing values, outliers, multicollinearity handled.

✅ Feature Engineering: Transaction type encoding + delta features for money flow.

✅ Model: XGBoost with hyperparameter tuning, early stopping, and SMOTE resampling.

✅ Evaluation: Precision-Recall AUC (AUPRC), ROC-AUC, F1, Confusion Matrix.

✅ Explainability: Feature importance & SHAP for interpreting fraud signals.

✅ Prevention Plan: Infrastructure updates, step-up controls, monitoring & governance.
-----------------------
📊 Results

Fraud detection framed as binary classification with imbalance handling.

Key predictors: high transaction amounts, deltaOrig/deltaDest anomalies, CASH_OUT & TRANSFER types, and temporal bursts.

Performance measured using AUPRC & Recall to prioritize catching fraud cases.
----------------------
🛠️ Tech Stack

Languages/Libraries: Python, Pandas, NumPy, Scikit-learn, XGBoost, imbalanced-learn

Visualization: Matplotlib, Seaborn

Evaluation: Precision-Recall Curves, ROC, SHAP
