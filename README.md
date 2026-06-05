# Customer Churn Analysis Using Python & Tableau

## Overview
This project analyzes gym membership data to identify factors associated with customer retention and churn. The goal is to use Python-based data analysis and visualization to determine which member characteristics are most related to churn risk.

## Dashboard Preview

![Dashboard Preview](dashboard_overview.png)

## Interactive Tableau Dashboard

View the interactive dashboard on Tableau Public:

[Tableau Dashboard](https://public.tableau.com/views/GymMembershipRetentionChurnAnalysis/CustomerRetentionChurnAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The dataset contains gym member information, including gender, age, location proximity, referral participation, employer partnership status, contract period, and churn status.

## Project Workflow
1. Loaded and reviewed the raw CSV dataset.
2. Cleaned and transformed the data using Pandas.
3. Created readable labels for churn and demographic fields.
4. Calculated overall churn rate and churn rates by customer segment.
5. Built visualizations to compare retention patterns.
6. Summarized key findings and future improvements.

## Key Findings
- Members with 1-month contracts experienced a 42% churn rate.
- Members with 12-month contracts experienced only a 2% churn rate.
- Members located near the gym churned at a rate of 24%, compared to 40% for members located farther away.
- Referred members churned at a rate of 16%, compared to 31% for non-referred members.
- Younger members experienced significantly higher churn rates than older members.

## Visualizations
Visualizations created in the notebook are saved in the `images/` folder, including:
- Retention by gender
- Retention by location proximity
- Retention by employer partnership
- Retention by referral program
- Churn by age

## Repository Structure

```text
customer-churn-analysis-python/
├── customer_churn_analysis.ipynb
├── gym_churn.csv
├── dashboard_overview.png
├── requirements.txt
└── README.md
```

## Business Impact

The analysis identified several factors associated with customer retention. Findings suggest that longer contract commitments, referral participation, and geographic proximity to the gym are strongly associated with lower churn rates. These insights could support targeted retention strategies and membership program improvements.

## Skills Demonstrated

- Data Cleaning
- Data Analysis
- Data Visualization
- Exploratory Data Analysis (EDA)
- Python Programming
- Tableau Dashboard Development
- Business Intelligence Reporting
- Statistical Analysis

## Future Improvements
- Build a machine learning model to predict churn.
- Add time-based membership data to analyze seasonal churn trends.
- Compare churn across different gyms, locations, or programs.
