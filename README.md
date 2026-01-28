# Business Analysis: Marketing Optimization for Showz

This repository contains a comprehensive analysis focused on optimizing marketing expenses for **Showz**, a company dedicated to selling event tickets. Through cohort-based data analysis and business metrics, the goal is to identify user behavior patterns and profitability.

## Project Objective

In this analysis, the objective is to determine the efficiency of marketing investments by investigating:
* Customer service usage behavior.
* Purchase cycle (when they start their first purchase).
* Profitability per customer (**LTV** - Customer Lifetime Value).
* Break-even point between revenue and acquisition costs (**CAC** - Customer Acquisition Cost).

## Data Used

The analysis is based on three key datasets from the 2017-2018 period:
1.  **Visits**: Detailed server session records (device, traffic source, start and end times).
2.  **Orders**: Transaction history of users.
3.  **Costs**: Marketing investment statistics broken down by source and date.

## Analysis Summary

The project follows a logical data analysis structure:
*   **Data Processing**: Cleaning, type conversion, and memory optimization.
*   **Exploratory Data Analysis (EDA)**: Analysis of active users (DAU, WAU, MAU) and retention metrics.
*   **Metric Calculation**:
    *   Revenue generation by cohort.
    *   CAC calculation by source.
    *   ROI/ROMI analysis to determine each channel's effectiveness.

## Main Conclusions

Throughout the investigation, marketing channels with different levels of effectiveness have been identified. We observed when cohorts start becoming profitable for the business and recommended adjustments in budget distribution to maximize return on investment.

---

### Technologies Used
*   Python 3.x
*   Pandas (Data analysis and manipulation)
*   Matplotlib & Seaborn (Visualization)
*   Cohort Analysis (LTV and Retention calculation)
