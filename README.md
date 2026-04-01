# 🏦 Customer Churn Prediction — Credit Card Platform

> Predicting customer attrition using Machine Learning to help banks 
> retain customers before they leave.

## Problem Statement
A digital bank loses revenue every time a credit card customer leaves. 
This project predicts **which customers are at risk of churning** 
so the bank can take proactive action.

## Results
| Model | Accuracy | ROC-AUC | F1-Score |
|-------|----------|---------|----------|
| Logistic Regression | 90.3% | 0.892 | 0.73 |
| Random Forest | 96.2% | 0.978 | 0.91 |
| **XGBoost (Final)** | **97.5%** | **0.982** | **0.95** |

## How to Run
1. Clone this repository:
```
   git clone https://github.com/Shruusharma/customer-churn-prediction.git
```
2. Install dependencies:
```
   pip install -r requirements.txt
```
3. Download dataset from [Kaggle](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers) 
   and place `BankChurners.csv` in the `data/` folder
4. Run the app:
```
   streamlit run app.py
```

## Project Structure
- `notebooks/` — Jupyter notebooks with full analysis
- `src/` — Clean Python source code
- `app.py` — Streamlit web application
- `models/` — Saved trained model

## Tech Stack
Python | XGBoost | SHAP | Streamlit | scikit-learn | pandas

## Authors
Shruti Sharma — Anand International College of Engineering
