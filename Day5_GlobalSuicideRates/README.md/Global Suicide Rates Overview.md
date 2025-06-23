# 🌍 Global Suicide Rates Overview (1985-2016) - Day 5 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze global suicide rates from 1985 to 2016 to understand trends over time, regional and gender differences, age group patterns, and their relation to socio-economic indicators.

## Dataset  
- **Source:** Suicide Rates Overview 1985 to 2016 (Kaggle)  
- **Format:** CSV (long format)  
- **Features:**  
  - country  
  - year  
  - sex  
  - age  
  - suicides_no  
  - population  
  - suicides/100k pop  
  - country-year  
  - HDI for year  
  - gdp_for_year ($)  
  - gdp_per_capita ($)  
  - generation  

## Methods  
- Cleaned data by:
  - Removing invalid or inconsistent values.
  - Handling missing values, particularly in `HDI for year`.
  - Converting GDP and population columns to numeric types.
- Enriched data by:
  - Adding `Continent` (via manual mapping).
- Visualizations:
  - Line plot: Global suicide rate over time.
  - Bar plot: Average suicide rates by continent.
  - Bar plot: Top 10 and bottom 10 countries (average suicide rate across years).
  - Box plot: Suicide rate distribution by gender and age group.
  - Scatter plot: GDP per capita vs. suicide rate (sample year).
  - Pie chart: Proportion of suicides by continent.

## Key Insights  
- **Global trend:** Suicide rates fluctuated over the years, with some decline towards 2016.  
- **Gender disparity:** Males have significantly higher suicide rates across most countries and age groups.  
- **Regional pattern:** Europe shows the highest average suicide rates; Africa and Latin America tend to have lower averages.  
- **Socio-economic links:** Weak to moderate negative correlation between GDP per capita and suicide rate (higher GDP, lower suicide rate in general).

## Output  
- Visualizations saved for presentations and social media.  
- CSV files:  
  - `suicide_rates_by_continent.csv`: Aggregated suicide metrics by continent  
  - `suicide_rates_correlation.csv`: Correlation results  

## Next Steps  
- Time series forecasting for global suicide trends.  
- Build interactive dashboards (e.g. Streamlit / Plotly Dash) to explore patterns dynamically.

---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!
