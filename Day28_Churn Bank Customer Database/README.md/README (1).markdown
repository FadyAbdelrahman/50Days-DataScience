# 📌 Churn Bank Customer Database - Day 28 of 50 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze the Churn Bank Customer Database to understand customer churn patterns, demographic differences, and their relation to account activity and financial indicators.

## Dataset  
- **Source:** Churn Modelling Dataset (Kaggle)  
- **Format:** CSV  
- **Features:**  
  - RowNumber  
  - CustomerId  
  - Surname  
  - CreditScore  
  - Geography  
  - Gender  
  - Age  
  - Tenure  
  - Balance  
  - NumOfProducts  
  - HasCrCard  
  - IsActiveMember  
  - EstimatedSalary  
  - Exited  

## Methods  
- Cleaned data by:  
  - Checking for missing values.  
  - Ensuring data types are appropriate for analysis.  
- Enriched data by:  
  - Grouping by geography, gender, and other attributes.  
- Visualizations:  
  - Bar plot: Distribution of customers by geography.  
  - Line plot: Average balance by age.  
  - Bar plot: Customer exit status by gender.  
  - Bar plot: Exited customers by geography.  

## Key Insights  
- **Gender Distribution:** Males make up the majority of customers (5,457 vs. 4,543 females).  
- **Churn and Balance:** Customers who exited the bank had a higher average balance ($91,105) compared to those who stayed ($72,745).  
- **Product Ownership:** Most customers own 1 or 2 bank products.  
- **Activity and Products:** Active customers have a slightly higher average number of products (1.54 vs. 1.53 for inactive).  
- **Regional Patterns:** France has the highest number of customers (5,014), followed by Spain (2,477) and Germany (2,509).  

## Output  
- Visualizations saved for presentations and social media.  
- CSV files:  
  - `churn_by_geography.csv`: Aggregated churn metrics by geography  
  - `balance_by_age.csv`: Average balance by age group  
---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!