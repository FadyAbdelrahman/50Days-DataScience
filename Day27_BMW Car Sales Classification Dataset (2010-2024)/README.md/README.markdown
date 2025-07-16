# 🚗 BMW Car Sales Classification Dataset (2010-2024) - Day 27 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze BMW car sales data from 2010 to 2024 to understand sales trends, regional differences, and the impact of various features on sales classification.

## Dataset  
- **Source:** BMW Car Sales Classification Dataset (2010-2024)  
- **Format:** CSV  
- **Features:**  
  - Model  
  - Year  
  - Region  
  - Color  
  - Fuel_Type  
  - Transmission  
  - Engine_Size_L  
  - Mileage_KM  
  - Price_USD  
  - Sales_Volume  
  - Sales_Classification  

## Methods  
- Cleaned data by:  
  - Checking for missing values.  
  - Standardizing column names.  
- Enriched data by:  
  - Grouping by model, region, and other categories.  
- Visualizations:  
  - Pie chart: Distribution of fuel types.  
  - Bar plot: Number of cars by model year range.  
  - Line plot: Average price by year.  
  - Heatmap: Price vs. mileage.  

## Key Insights  
- **Top Models:** The 7 Series leads in total sales volume, followed by the 18 and X1 models.  
- **Regional Sales:** Asia has the highest total sales volume, with 42,974,277 units sold.  
- **Fuel Types:** Diesel cars have the highest average engine size (3.25L), while electric cars have the lowest (3.24L).  
- **Transmission Preferences:** Manual transmissions slightly outnumber automatic ones, with 25,154 manual cars sold compared to 24,846 automatic.  
- **Pricing Trends:** The average price of BMW cars has remained relatively stable over the years, with slight fluctuations.  
- **Sales Classification:** High sales classification cars have a slightly lower average price ($74,966) compared to low sales classification cars ($75,064).  

## Output  
- Visualizations saved for presentations and social media.  
- CSV files:  
  - `sales_by_model.csv`: Aggregated sales metrics by model  
  - `sales_by_region.csv`: Sales volume by region  

## Next Steps  
- Time series forecasting for future sales trends.  
- Build interactive dashboards (e.g., Streamlit / Plotly Dash) to explore patterns dynamically.

---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!