# 🌍 Global Economic Indicators (2010–2025) - Day 9 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze 16 years of global macroeconomic indicators to uncover patterns in inflation, GDP growth, unemployment, taxation, public debt, and regional economic trends using Python and visual analytics.

## Dataset  
- **Title:** Global Economic Indicators (2010–2025)  
- **Source:** [World Bank Open Data](https://data.worldbank.org/)  
- **Format:** CSV  
- **Size:** 3,472 rows × 16 columns  
- **Key Columns:**  
  - `country_name`, `country_id`, `year`  
  - `Inflation (CPI %)`, `GDP (Current USD)`, `GDP per Capita (Current USD)`  
  - `Unemployment Rate (%)`, `Interest Rate (Real, %)`  
  - `Government Expense (% of GDP)`, `Government Revenue (% of GDP)`  
  - `Public Debt (% of GDP)`, `Tax Revenue (% of GDP)`

## Methods  
- Cleaned missing values using forward-fill and backward-fill techniques  
- Added `continent` classification based on country mappings  
- Created visual comparisons across indicators and regions  
- Performed the following analyses:

### 📊 General Analysis  
- Year-over-year inflation and GDP growth trends  
- Top 10 countries with highest inflation in 2023  
- Countries with lowest GDP growth in 2023  
- Average unemployment by continent  
- Ranking by government spending and tax revenue  
- Public debt distribution in 2023 and 2025  
- Country-level economic trajectories (e.g., Sudan, Ireland, Japan)

### 📈 Advanced Analysis  
- Correlation heatmap among economic indicators  
- Comparative trends between GDP growth and inflation  
- Regional economic shifts (Africa, Asia, Europe)  
- Cluster analysis by macroeconomic similarity  
- Forecasting trends using regression models

## Key Insights  
- **Sudan** and **Argentina** have experienced the highest inflation  
- **GDP growth volatility** is common among developing countries  
- **Europe and North America** show more fiscal stability  
- **Asia's economies** (e.g., China, India) maintain strong growth momentum  
- **Public debt** is rising in several developed and developing nations  
- **Tax and spending ratios** reveal varying economic strategies by region

## Output  
- Visualizations (matplotlib/seaborn):  
  - Line plots, bar charts, heatmaps  
  - Comparative graphs by continent and country  
 

---

This work is part of my **50 Days of Python + Data Science Challenge**.  
Follow along for more projects and insights!
