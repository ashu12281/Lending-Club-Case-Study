
# EDA Case Study: Loan Default Prediction

## General Information
This project explores a dataset from a consumer finance company to identify patterns in loan defaults using Exploratory Data Analysis (EDA). The objective is to help minimize credit loss by identifying risky borrowers using historical data.

## Dataset
- Source: Lending platform (2007–2011)
- Key Field: `loan_status` ("Fully Paid", "Charged Off", "Current")
- Total Records: ~39,000
- Features: 111 before cleaning

## Business Problem
Defaulting customers cause credit loss. Early identification of such borrowers allows the company to:
- Reject loan
- Reduce loan amount
- Charge higher interest

## Conclusions
- `Grade` and `Sub_grade` strongly correlate with default.
- `Interest Rate` is higher for defaulting loans.
- `Debt-to-Income (DTI)` above 20 is riskier.
- `Purpose` like “small_business” has a higher default rate.

## Technologies Used
- Python 3.8+
- Pandas 1.5+
- NumPy 1.23+
- Matplotlib 3.7+
- Seaborn 0.12+
- Jupyter Notebook

## Acknowledgements
Inspired by credit risk analytics problems in finance.
Based on EDA case study from learning programs.
