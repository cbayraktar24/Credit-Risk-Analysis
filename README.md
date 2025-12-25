# Credit Risk Analysis Project

NBViewer link:
https://nbviewer.org/github/cbayraktar24/Banking-Data-Analysis/blob/main/Credit_Risk_Analysis_FINAL.ipynb

## Project Overview
This project analyzes consumer loan data to identify key drivers of default risk and build a baseline credit risk model using logistic regression.

## Dataset
- Source: https://www.kaggle.com/datasets/laotse/credit-risk-dataset
- Dataset file used locally: credit_risk_dataset.csv
- Observations: ~32,000 loans
- Target variable: loan_status (0 = non-default, 1 = default)

## Tools Used
- Python (pandas, numpy)
- Data visualization (matplotlib, seaborn)
- Machine learning (scikit-learn)

## Key Findings
- Default rates increase monotonically with higher interest rates.
- Higher income borrowers consistently show lower default risk.
- Default risk is highest for very large loans and also elevated for very small loans.
- Employment length shows a U-shaped relationship with default, with the lowest risk in mid-career borrowers.
- Loan percent of income is the strongest numeric predictor of default.

## Modeling
- Built a baseline logistic regression model.
- Applied class weighting to address class imbalance and improve default detection.
- Demonstrated trade-offs between precision and recall based on business risk appetite.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook

