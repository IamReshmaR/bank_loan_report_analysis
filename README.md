# bank_loan_report_analysis
Data analysis project using Tableau and SQL to create a comprehensive Bank Loan Report
## Overview
This project involves analyzing bank loan data using SQL and Tableau to generate comprehensive insights. It includes various KPIs, visualizations, and dashboards to monitor loan portfolio performance and identify trends.

## Features
- **Dashboards:** Interactive Tableau dashboards:
  1. **Summary Dashboard**: Key metrics such as total loan applications, funded amounts, and received amounts.
  2. **Overview Dashboard**: Visualizations including line charts, bar charts, tree maps, and more.
  3. **Details Dashboard**: A consolidated view of loan-related metrics.
- **SQL Queries**: Includes scripts for calculating KPIs and filtering data.

## Dashboards
### Summary Dashboard
- Tracks Month-to-Date (MTD) and Month-over-Month (MoM) changes.
- KPIs include:
  - Total Loan Applications
  - Funded Amount
  - Amount Received
  - Average Interest Rate
  - Debt-to-Income Ratio

### Overview Dashboard
- Monthly trends: Line chart showing loan applications, funded amounts, and received amounts.
- Regional analysis: Filled map highlighting metrics by state.
- Other insights: Loan term, employee length, and loan purpose breakdowns.

### Details Dashboard
- Comprehensive grid view of metrics categorized by loan status, enabling detailed analysis.

## SQL Queries
The SQL scripts included in this repository are used to calculate:
- Loan performance KPIs (Good vs. Bad Loans).
- Aggregated metrics based on various filters (e.g., grade, state).

## How to Use
1. Open the Tableau `.twbx` file to explore interactive dashboards.
2. Run SQL scripts provided in the `queries.sql` file to analyze data directly.
