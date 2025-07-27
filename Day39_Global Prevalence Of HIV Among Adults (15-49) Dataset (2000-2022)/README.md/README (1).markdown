# 🌍 Global Prevalence Of HIV Among Adults (15-49) Dataset (2000-2022) - Day 39 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze the global prevalence of HIV among adults aged 15-49 from 2000 to 2022 to understand trends over time, regional differences, and continental patterns.

## Dataset  
- **Source:** Global Prevalence Of HIV Among Adults (15-49) Dataset (2000-2022)  
- **Format:** CSV  
- **Features:**  
  - indicatorId  
  - geoUnit  
  - year  
  - value (HIV prevalence percentage)  

## Methods  
- Cleaned data by:  
  - Dropping unused columns (`qualifier` and `magnitude`)  
  - Verifying no missing values in key columns  
- Enriched data by:  
  - Adding `continent` based on `geoUnit` using a mapping  
- Visualizations:  
  - Line plot: Average HIV prevalence over time  
  - Bar plot: Average HIV prevalence by continent  
  - Pie chart: Distribution of average prevalence by decade  
  - Heatmap: HIV prevalence by year and geoUnit  
  - Line plot: Average HIV prevalence trend by continent  

## Key Insights  
- The global average HIV prevalence from 2000 to 2022 is 1.85%.  
- Africa has the highest average prevalence at 3.98%, significantly higher than other continents.  
- There is a general declining trend in HIV prevalence over the years.  
- In 2022, the highest HIV prevalence by continent ranges from 19.3% in Africa to 0.9% in Asia and Europe.  
- 16 geographic units have an average HIV prevalence greater than 5%.  

## Output  
- Visualizations saved for presentations and social media.  
---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!