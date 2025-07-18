# 🌍 Global Population Pulse 2025 - Day 30 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze global population data for 2025 to understand trends in population growth, density, and distribution across countries.

## Dataset  
- **Source:** World Population By Country (Kaggle)  
- **Format:** CSV  
- **Features:**  
  - country  
  - pop2025  
  - pop2050  
  - area  
  - landAreaKm  
  - cca2  
  - cca3  
  - density  
  - growthRate  
  - worldPercentage  
  - rank  

## Methods  
- Cleaned data by:  
  - Handling missing values, particularly in `cca2`.  
  - Standardizing country codes.  
- Enriched data by:  
  - Grouping by country, rank, and growth rate bins.  
- Visualizations:  
  - Bar plot: Countries with population over 100 million in 2025.  
  - Histogram: Distribution of population density.  
  - Line plot: Average population by rank.  

## Key Insights  
- **Global Population:** Projected to reach 8.23 billion by 2025.  
- **Top Countries:** India leads with 1.46 billion, followed by China with 1.42 billion.  
- **Growth Rates:** Average global growth rate is 0.86%, with 62 countries experiencing negative growth.  
- **Density:** Macau has the highest population density at 21,945 people per square kilometer.  
- **Land Area:** Russia has the largest land area, covering over 17 million square kilometers.  

## Output  
- Visualizations saved for presentations and social media.  
- CSV files:  
  - `population_by_country.csv`: Aggregated population metrics by country  
  - `population_correlation.csv`: Correlation results  
---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!