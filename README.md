# Retail SME Financial Health Dashboard

A Power BI dashboard analyzing the financial health of a small retail and
trading business, covering 36 months of income statement, balance sheet,
and cash flow data.

## Objective

Build an interactive dashboard giving SME owners and stakeholders a clear,
real-time view of financial performance: revenue trends, profitability,
expense breakdown, and balance sheet health, supporting better budgeting
and financial planning decisions.

## Dataset

A synthetic 36-month dataset (Jan 2023 - Dec 2025) modeling a small retail
SME in USD, built to be internally consistent: the balance sheet balances
exactly every month, and the cash flow statement ties out to the balance
sheet's cash position throughout. Full methodology and assumptions are
documented in `Dataset_Documentation.pdf`.

## Dashboard

**Retail SME Financial Health Dashboard**
![Retail SME Financial Health Dashboard](Retail-SME-Financial-Health-Dashboard/blob/main/Retail%20SME%20Financial%20Health%20Dashboard.png)

**Retail SME Balance Sheet Overview**
![Retail SME Balance Sheet Overview](screenshots/Retail%20SME%20Balance%20Sheet%20Overview.png)

**Retail SME Data Model**
![Retail SME Data Model](screenshots/Retail%20SME%20Data%20Model.png)

## Key Insights

- Salaries & Wages account for the largest share of operating expenses,
  more than 4x the next-largest cost category.
- Net margins start thin in early 2023 and stabilize in the 12-17% range
  by 2024-2025, alongside steady revenue growth and a clear December
  seasonal peak each year.
- Total Assets and Total Liabilities + Equity track exactly in parity
  across all 36 months, confirming balance sheet integrity.

## Tools

Power BI Desktop, Power Query (data transformation), DAX (measures),
star schema data modeling.
