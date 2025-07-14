# Global Ecological Footprint (2016) - Day 26 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze the Global Ecological Footprint data from 2016 to understand countries' environmental impact, sustainability trends, and their relation to economic indicators like GDP per capita.

## Dataset  
- **Source:** Global Ecological Footprint 2016 (Kaggle)  
- **Format:** CSV  
- **Features:**  
  - country  
  - ecological_footprint_per_capita  
  - biocapacity_per_capita  
  - ecological_deficit_or_reserve  
  - gdp_per_capita  
  - population  
  - year  

## Methods  
- Cleaned data by:  
  - Removing invalid or inconsistent values.  
  - Handling missing values in `ecological_footprint_per_capita` and `biocapacity_per_capita`.  
  - Converting GDP and population columns to numeric types.  
- Enriched data by:  
  - Calculating total ecological footprint and biocapacity.  
- Visualizations:  
  - Bar plot: Top 10 countries by ecological footprint per capita.  
  - Scatter plot: Ecological footprint vs. GDP per capita.  
  - Choropleth map: Ecological deficit or reserve by country.  

## Key Insights  
- **Sustainability:** Countries with high ecological deficits rely heavily on external resources.  
- **Economic Links:** Positive correlation observed between GDP per capita and ecological footprint.  
- **Regional Patterns:** Developed regions like North America and Europe exhibit higher ecological footprints.  

## Output  
- Visualizations saved for presentations and social media.  
- CSV files:  
  - `footprint_by_country.csv`: Aggregated footprint metrics by country  
  - `footprint_correlation.csv`: Correlation results  
---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!