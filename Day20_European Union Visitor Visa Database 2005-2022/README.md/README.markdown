# 🌍 European Union Visitor Visa Database - Day 20 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Analyze the European Union visitor visa statistics from 2005 to 2022 to understand trends in applications, issuance, and refusal rates, and to explore regional and economic patterns in visa data.

## Dataset  
- **Source:** European Union Visitor Visa Database (2005-2022)  
- **Format:** CSV  
- **Features:**  
  - reporting_year  
  - reporting_state  
  - consulate_country  
  - consulate_country_code  
  - consulate_country_region  
  - consulate_country_income_group  
  - consulate_city  
  - visitor_visa_applications  
  - visitor_visa_issued  
  - visitor_visa_not_issued  
  - visitor_visa_refusal_rate  

## Methods  
- **Cleaned data by:**  
  - Handling missing values in `consulate_country_income_group` and `visitor_visa_refusal_rate`.  
  - Dropping rows with missing refusal rates.  
- **Enriched data by:**  
  - Calculating refusal rates where missing.  
- **Visualizations:**  
  - Bar chart: Total visa applications by year.  
  - Bar chart: Top 10 consulate countries by applications.  
  - Pie chart: Distribution of consulate regions.  
  - Heatmap: Refusal rates by region and year.  
  - Bar chart: Average refusal rate by income group.  

## Key Insights  
- **Application Trends:** Visa applications peaked in 2014 with 17,651,661 and saw a sharp decline in 2020 to 3,001,189 due to the pandemic.  
- **Top Countries:** The Russian Federation leads with 69,538,702 applications, followed by China and Ukraine.  
- **Refusal Rates:** Sub-Saharan Africa has the highest average refusal rate at 21.23%, while North America has the lowest at 3.14%.  
- **Income Group Impact:** Lower middle-income countries have the highest application volume but face higher refusal rates compared to high-income countries.  

## Output  
- **Visualizations saved for:**  
  - Total visa applications by year.  
  - Top 10 consulate countries by applications.  
  - Distribution of consulate regions.  
  - Refusal rates by region and year.  
  - Average refusal rate by income group. 
---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!