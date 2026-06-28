# 📊 Credit Risk Outcome Prediction Using Machine Learning

## Overview

This project presents an end-to-end machine learning framework for predicting borrower credit risk outcomes using the Lending Club loan dataset. It combines an empirical transition matrix benchmark with a Random Forest classifier and SHAP explainability to provide a transparent, interpretable, and data-driven approach to credit risk assessment.

Developed as part of my MSc Data Science dissertation.

---

## 🎯 Problem Statement

Traditional credit risk models primarily focus on default prediction, providing limited insight into varying levels of borrower risk. This project predicts multiple credit risk outcomes to support more informed lending decisions, portfolio monitoring, and financial risk management.

---

## 📂 Dataset

- **Source:** Lending Club Loan Dataset (Kaggle)
- **Period:** 2007–2018
- **Dataset Size:** ~2 million consumer loan records

---

## ⚙️ Methodology

- Data Cleaning & Preprocessing
- Feature Engineering
- Empirical Transition Matrix Benchmark
- Random Forest Classification
- Cross-Validation
- Hyperparameter Tuning (GridSearchCV)
- SHAP Explainability

---

## 📈 Results

- **Overall Model Accuracy:** **79%**
- Identified the most influential predictors of borrower risk:
  - Loan Term
  - Interest Rate
  - FICO Score
  - Debt-to-Income Ratio
- Improved model transparency through SHAP explainability.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SHAP
- Jupyter Notebook

---

## 📁 Repository Structure

```text
├── data/
├── notebooks/
├── images/
├── models/
├── dissertation/
├── requirements.txt
└── README.md
```

---

## 🚀 Future Improvements

- Compare additional machine learning models such as XGBoost and LightGBM.
- Deploy the model as an interactive Streamlit web application.
- Validate the framework using commercial banking datasets.

---

## 👨🏽‍💻 Author

**Chiagozie Erochukwu**

*MSc Data Science | Credit Risk Analytics | Machine Learning*
