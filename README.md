# 📊 Bank Loan Analysis

## Overview

The **Bank Loan Analysis** project analyzes historical loan data to evaluate lending performance, borrower behavior, and loan portfolio health. The project calculates business KPIs, identifies trends, classifies good and bad loans, and provides insights that can be used by financial institutions to make data-driven lending decisions.

The analysis is performed using **Python** in a Jupyter Notebook.

---

## Problem Statement

Banks receive thousands of loan applications every month. Analyzing this data helps answer questions such as:

- How many loan applications are received?
- How much money is funded?
- How much repayment has been received?
- What is the average interest rate?
- What percentage of loans are good or bad?
- Which states, loan purposes, employment lengths, and home ownership categories contribute most to lending?

This project generates KPIs and visualizations to answer these business questions.

---

## Objectives

- Analyze overall loan performance.
- Measure key lending KPIs.
- Classify Good Loans and Bad Loans.
- Analyze monthly lending trends.
- Study regional loan distribution.
- Evaluate borrower characteristics.
- Support business decision-making using data.

---

## Dataset

The project uses a financial loan dataset containing customer loan information such as:

- Loan ID
- Loan Amount
- Issue Date
- Loan Status
- Interest Rate
- Debt-to-Income Ratio (DTI)
- Total Payment
- State
- Employment Length
- Home Ownership
- Loan Purpose
- Loan Term

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

---

## Project Structure

```
Bank Loan Analysis/
│
├── Bank Loan Analysis.ipynb
├── financial_loan.xlsx
├── Problem Statement.pptx
└── README.md
```

---

## Key Performance Indicators (KPIs)

### Loan Performance

- Total Loan Applications
- Month-to-Date (MTD) Loan Applications
- Total Funded Amount
- MTD Funded Amount
- Total Amount Received
- MTD Amount Received
- Average Interest Rate
- Average Debt-to-Income Ratio (DTI)

### Good Loan KPIs

Loans with status:
- Fully Paid
- Current

Metrics:
- Good Loan Applications
- Good Loan Percentage
- Good Loan Funded Amount
- Good Loan Total Amount Received

### Bad Loan KPIs

Loans with status:
- Charged Off

Metrics:
- Bad Loan Applications
- Bad Loan Percentage
- Bad Loan Funded Amount
- Bad Loan Total Amount Received

---

## Visualizations

The project includes analysis such as:

- Monthly Loan Trends
- Regional Analysis by State
- Loan Term Distribution
- Employment Length Analysis
- Loan Purpose Breakdown
- Home Ownership Analysis

These visualizations help identify lending patterns and borrower characteristics.

---

## Workflow

1. Import required libraries.
2. Load the dataset.
3. Perform data exploration.
4. Clean and validate data.
5. Calculate business KPIs.
6. Analyze Good and Bad Loans.
7. Generate visualizations.
8. Draw business insights.

---

## Business Insights

The analysis helps financial institutions:

- Monitor loan portfolio performance.
- Identify high-risk loans.
- Track repayment trends.
- Understand customer borrowing behavior.
- Improve lending strategies.
- Support data-driven financial decisions.

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/Bank-Loan-Analysis.git
```

### Install dependencies

```bash
pip install pandas numpy matplotlib seaborn plotly openpyxl
```

### Run

Open the notebook:

```bash
jupyter notebook "Bank Loan Analysis.ipynb"
```

Run all cells sequentially.

---

## Future Improvements

- Interactive Power BI Dashboard
- Machine Learning model for loan default prediction
- Customer risk scoring
- Loan approval recommendation system
- Automated reporting dashboard

---

## Author

**Bhargavi Reddy**

Data Analyst | Python | SQL | Power BI | Excel | Machine Learning

---

## License

This project is developed for educational and portfolio purposes.
