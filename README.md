# Cisco-Product-Sales-Forecasting
Forecasting Cisco quarterly product sales using ML models

This project presents a machine learning pipeline for forecasting quarterly sales (or related metrics) of Cisco products. The objective is to compare multiple regression models on real-world data and assess their accuracy and bias in predicting future quarters.

## 📌 Overview

- Data Source: `CFL_DS2.xlsx` (Cisco Forecast League dataset)
- Target Variables: Forecasted values for `FY24 Q3`, `FY24 Q4`, `FY25 Q1`, `FY25 Q2`
- Feature Engineering: Handles both numerical and categorical data with preprocessing
- Models Used:
  - Random Forest Regressor
  - Linear Regression
  - Gradient Boosting Regressor
  - Decision Tree Regressor
- Custom Evaluation:
  - **Bias**: Mean percentage error between prediction and actual
  - **Accuracy**: Custom metric based on relative closeness to true value

## ⚙️ Setup

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn openpyxl
