# Enterprise-Turnover-Analytics

**[View Live Dashboard](https://public.tableau.com/app/profile/janhavi.chaudhari/viz/Enterprise-Turnover-Analytics_/Dashboard1)**

## Overview
An end-to-end data pipeline and visual analytics project tracking employee flight risk. The architecture processes raw HR data into predictive business intelligence to identify structural and behavioral drivers of turnover.

## Technical Architecture
* **Data Engineering (Python/Pandas):** Processed HR datasets and engineered categorical features into numerical binaries for advanced aggregation.
* **Backend Analytics (SQL via Python):** Executed automated SQL pipelines utilizing Common Table Expressions (CTEs) and Window Functions to calculate departmental risk variances against corporate baselines.
* **Frontend Visualization (Tableau):** Developed an interactive dashboard mapping departmental variance, lifecycle attrition spikes, and job satisfaction correlations.

## Key Insights
* **Departmental Variance:** The Sales unit operates at a +5.32% variance above the organizational attrition baseline.
* **Lifecycle Risk:** Attrition probability peaks significantly at the 1-to-2-year tenure mark.
* **Behavioral Correlation:** Quantitative analysis confirms a direct correlation between lowest job satisfaction (Level 1) and terminal attrition rates.
