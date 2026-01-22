# Dynamic Risk Tolerance Monitoring

## Overview
This project analyzes borrower risk behavior using LendingClub loan data and develops a
dynamic risk tolerance scoring framework based on financial and credit indicators.

The objective is to demonstrate how borrower risk is not static and evolves over time due
to changes in income, credit utilization, repayment behavior, and interest rates.

---

## Dataset
- **Source:** LendingClub Accepted Loans Dataset (2007–2018)
- **Records used:** 200,000 (sampled due to memory constraints)
- **Time period analyzed:** 2015
- **Total features:** 21

---

## Project Structure
# Dynamic Risk Tolerance Monitoring

## Overview
This project analyzes borrower risk behavior using LendingClub loan data and develops a
dynamic risk tolerance scoring framework based on financial and credit indicators.

The objective is to demonstrate how borrower risk is not static and evolves over time due
to changes in income, credit utilization, repayment behavior, and interest rates.

---

## Dataset
- **Source:** LendingClub Accepted Loans Dataset (2007–2018)
- **Records used:** 200,000 (sampled due to memory constraints)
- **Time period analyzed:** 2015
- **Total features:** 21

---

## Project Structure

dynamic-risk-tolerance-monitoring/
│
├── data/
│   └── lending_club.csv
│
├── notebooks/
│   └── risk_analysis.ipynb
│
├── outputs/
│   └── charts/
│       ├── risk_distribution.png
│       └── dynamic_risk_trend.png
│
├── report/
│   └── final_report.pdf
│
├── README.md
└── .gitignore

## Key Results

- Mean risk score: ~35.9
- Majority of borrowers fall under Moderate Risk Tolerance
- Credit score (FICO) is the strongest risk determinant
- Portfolio risk shows noticeable monthly variation

## How to Run

1. Clone the repository
2. Install required libraries:
   pip install pandas numpy scikit-learn matplotlib seaborn
3. Open notebooks/risk_analysis.ipynb
4. Run all cells to reproduce results

