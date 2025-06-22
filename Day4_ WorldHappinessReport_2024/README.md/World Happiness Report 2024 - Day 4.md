# 🌍 World Happiness Report 2024 - Day 4 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze the World Happiness Report 2024 data to understand global happiness trends, regional patterns, and key contributing factors using data visualizations.

## Dataset  
- **Source:** World Happiness Report 2024  
- **Format:** CSV (wide format)  
- **Features:**  
  - Country name  
  - Ladder score  
  - upperwhisker / lowerwhisker  
  - Explained by: Log GDP per capita, Social support, Healthy life expectancy, Freedom to make life choices, Generosity, Perceptions of corruption  
  - Dystopia + residual  

## Methods  
- Cleaned data by handling missing values and inconsistencies.  
- Added logical classifications:
  - Region (e.g., Europe, Asia, Africa — added via manual mapping)
  - Happiness level (Low, Medium, High, Very High — based on Ladder score bins)
- Visualizations:
  - Bar plot: Top 10 happiest countries
  - Bar plot: Bottom 10 countries
  - Box plot: Happiness scores by region
  - Heatmap: Correlation between happiness factors
  - Scatter plots: Example: GDP per capita vs. Ladder score, social support vs. Ladder score  

## Key Insights  
- **Global trend:** Nordic countries continue to dominate happiness rankings, with Finland at the top.  
- **Regional differences:** Europe and Oceania have higher average happiness scores; African countries are predominantly in the lower tiers.  
- **Drivers:** GDP per capita and social support exhibit the strongest positive associations with Ladder score.  
- **Disparities:** Noticeable gaps in happiness levels between regions highlight inequalities.

## Output  
- Visualizations saved for reports and social sharing.  
- CSV files:  
  - `happiness_by_region.csv`: Aggregated happiness metrics by region  
  - `happiness_factors_correlation.csv`: Correlation matrix of contributing factors  

## Next Steps  
- Perform clustering to identify distinct country happiness profiles.  
- Develop interactive dashboards to better communicate findings.

---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!
