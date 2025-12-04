# Behaviourally-Augmented-Credit-Default-Prediction-Model
A risk-scoring model that compares traditional models (Logit, Probit) with behaviourally-augmented ML models (XGBoost, LightGBM). Shows whether behavioural features improve PD prediction.

# Behaviourally-Augmented Credit Default Prediction Model
*A Machine Learning Credit Risk Study Incorporating Behavioural Finance Indicators*


## Overview
This project investigates whether **behavioural features** improve the accuracy of credit default prediction models. Traditional credit scoring relies on demographic and financial variables. Behavioural finance research suggests borrower psychology—such as present bias, overconfidence, and spending volatility—affects credit behaviour and default likelihood.


This repository compares:
- **Traditional statistical models** (Logit)
- **Machine learning models** (Random Forest, XGBoost, LightGBM)
- **Behaviourally-enhanced ML models**


## Objectives
1. Build a baseline PD model.
2. Engineer behavioural features.
3. Compare model performance.
4. Build an interactive Streamlit credit scoring dashboard.
5. Provide model interpretation via SHAP values.


## Data Sources
- LendingClub Loan Data
- Prosper Loan Data
- Kaggle Credit Card Dataset
- Google Trends behaviour proxies


## Behavioural Features
| Feature | Behaviour Proxy |
|--------|------------------|
| Minimum Payment Ratio | Present bias |
| Spending Volatility | Self-control issues |
| Utilization Slope | Overconfidence |
| Late Payment Count | Inertia |
| Search Trends | Sentiment & anxiety |


## Dashboard
Run using:
```bash
streamlit run dashboard/app.py
