# 🌍 Global Innovation Index (GII) - Day 3 EDA

## Author
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal
Explore and analyze the Global Innovation Index (GII) data from 2011 to 2024 to understand country performance trends, volatility, and distribution patterns using data visualizations.

## Dataset
- **Source:** Global Innovation Index (2011-2024)  
- **Format:** Long format TSV  
- **Features:** Country, Year, Rank, Score  

## Methods
- Cleaned data by removing invalid values (`-1` in Rank/Score).
- Added logical classifications:
  - Region (e.g., Europe, Asia, Africa)
  - Performance Category (Low, Medium, Good, Excellent)
- Visualizations:
  - Line plot with error bars (global mean ± std over time)
  - Pie chart (performance categories in 2024)
  - Bar plot (top and bottom performers 2024)
  - Heatmap (score trends for selected countries)
- Volatility analysis:
  - Standard deviation of score and rank for countries with ≥5 years of data
- Correlation analysis:
  - Pearson correlation between year and score

## Key Insights
- **Global trend:** Average innovation score has been relatively stable with slight fluctuations over time.
- **Top performers 2024:** Countries like USA, Germany, and Singapore continue to rank highly.
- **Volatility:** Some countries show high year-on-year score volatility, reflecting inconsistent innovation performance.
- **Correlation:** Weak positive correlation between year and score (suggesting minor global improvement).

## Output
- Visualizations saved for use in publications and reports.
- CSV files:
  - `gii_volatility_enhanced.csv`: Volatility analysis results

## Next Steps
- Explore clustering countries by performance patterns.
- Create interactive dashboards or maps for better storytelling.

---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!
