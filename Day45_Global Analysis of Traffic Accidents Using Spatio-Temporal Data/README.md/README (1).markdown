# 🌍 Global Analysis of Traffic Accidents Using Spatio-Temporal Data - Day 45 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze global traffic accident data to understand patterns over time, identify high-risk locations, and examine the impact of weather, road conditions, and other factors on accident severity.

## Dataset  
- **Source:** Global Traffic Accidents Dataset
- **Format:** CSV  
- **Features:**  
  - Accident ID  
  - Date  
  - Time  
  - Location  
  - Latitude  
  - Longitude  
  - Weather Condition  
  - Road Condition  
  - Vehicles Involved  
  - Casualties  
  - Cause  

## Methods  
- Cleaned data by:  
  - Checking for missing values (none found in key columns).  
  - Converting `Date` to datetime format for temporal analysis.  
- Enriched data by:  
  - Extracting `Country` from `Location` using string splitting.  
- Visualizations:  
  - Bar plot: Accident distribution by weather condition.  
  - Line plot: Accidents by month in 2024.  
  - Pie chart: Top 5 causes of accidents.  
  - Box plot: Casualties by road condition.  
  - Line plot: Accidents by day in 2023.  

## Key Insights  
- **High-risk cities:** São Paulo, Brazil (1032 accidents), New York, USA (1016), and Beijing, China (1014) lead in accident counts.  
- **Cause impact:** Distracted driving has the highest average casualties per accident (5.10), followed by speeding (5.00).  
- **Weather influence:** 49.93% of accidents occur in bad weather (rain, storm, snow).  
- **Peak day:** February 22, 2023, had the most accidents in 2023.  
- **Weekend trend:** 2385 accidents occurred on weekends, slightly higher than weekdays.  

## Output  
- Visualizations saved for presentations and social media.  
---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!