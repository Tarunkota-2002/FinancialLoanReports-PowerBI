# FinancialLoanReports-PowerBI

**📊 Financial Loans Report – Power BI Dashboard**
=====================================================

This project presents an interactive Financial Loans Analysis Dashboard built using Power BI. It provides deep insights into loan performance, borrower behavior, and risk metrics to support data-driven decision-making in financial institutions.


**🚀 Project Overview**
================================

The dashboard analyzes loan data to uncover key trends such as:

**📊 Metrics Displayed**
=============================

Each visualization is supported by key metrics:

Total Loan Applications

Total Funded Amount

Total Amount Received

**📈 Charts & Visual Analysis**
=================================

The dashboard includes the following visualizations to uncover key lending insights:

**Monthly Trends by Issue Date (Line Chart)**
Highlights seasonality and long-term trends in loan activity.

**Regional Analysis by State (Filled Map)**
Identifies high-performing regions and regional disparities in lending.

**Loan Term Analysis (Donut Chart)**
Shows the distribution of loans across different term lengths.

**Employee Length Analysis (Bar Chart)**
Examines how lending metrics vary with borrower employment history.

**Loan Purpose Breakdown (Bar Chart)**
Provides insights into the primary reasons for loan applications.

**Home Ownership Analysis (Tree Map)**
Visualizes the impact of home ownership on loan applications and funding.

**🧮 DAX Measures & Calculations**
=====================================

The dashboard leverages DAX (Data Analysis Expressions) to create dynamic and insightful calculations:

**Aggregation Functions**
==========================
Used to compute core metrics:

COUNT() / COUNTROWS() → Total Loan Applications

SUM() → Total Funded Amount, Total Amount Received

AVERAGE() → Average Interest Rate, Average DTI

**Time Intelligence Functions**
================================
Enable trend analysis and period comparisons:

DATESMTD() → Month-to-Date (MTD) calculations

DATEADD() → Month-over-Month (MoM) comparisons

TOTALMTD() → Cumulative monthly metrics

CALCULATE Function
Applies filters and modifies context for dynamic KPI calculations.

DIVIDE Function
Safely performs division (e.g., ratios) while handling divide-by-zero errors.

FILTER Function
Creates conditional calculations for more refined analysis.
