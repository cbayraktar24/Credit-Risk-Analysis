# Credit Risk Analysis Project

## Project Overview
This project analyzes consumer loan data to identify key drivers of default risk and build a baseline credit risk model using logistic regression.

## Dataset
- Source: Kaggle Credit Risk Dataset
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
1. Install required libraries.
2. Run the Jupyter notebook from top to bottom.
