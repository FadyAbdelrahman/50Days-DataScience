# Global Crop Yield Forecast 2025: Analysis and Prediction Using 1990–2013 Data - Day 49 EDA

**Date:** August 6, 2025

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Analyze historical crop yield data from 1990 to 2013 to predict global crop yields for 2025, uncovering patterns in yield distribution, environmental factors, and geographic variations using Python and machine learning techniques.

## Dataset  
- **Title:** Global Crop Yield Dataset (1990–2013)    
- **Format:** CSV   
- **Key Columns:**  
  - `Area`, `Item`, `Year`  
  - `hg/ha_yield` (crop yield in hectograms per hectare)  
  - `average_rain_fall_mm_per_year`  
  - `pesticides_tonnes`  
  - `avg_temp` (average temperature in Celsius)

## Methods  
- Cleaned the dataset by checking for and handling missing values  
- Standardized column names and formats for consistency  
- Performed feature engineering by grouping data by area, crop type, and year  
- Trained a Linear Regression model using historical data to predict crop yields for 2025 based on environmental factors like rainfall, pesticide usage, and temperature  
- Conducted the following analyses:

### General Analysis  
- Top 5 crop types by average yield  
- Areas with the highest average yields  
- Distribution of yields across different years  
- Impact of rainfall and temperature on yield  

### Predictive Modeling  
- Trained a Linear Regression model to forecast 2025 yields  
- Evaluated model performance using training and test data  
- Predicted yields for 2025 based on average environmental factors  

## Key Insights  
- **Top Crops by Yield:** Cassava leads with an average yield of 150,479 hg/ha, followed by Potatoes (89,301 hg/ha) and Sweet Potatoes (119,091 hg/ha)  
- **Highest Yielding Areas:** The United Kingdom has the highest average yield at 240,956 hg/ha, followed by Belgium and Denmark  
- **2025 Predictions:** The model predicts significant yield increases for crops like Sorghum in Albania, with a projected yield change of over 990%  
- **Environmental Impact:**  
  - Areas with rainfall above 1,000 mm/year have an average yield of 76,903 hg/ha  
  - Optimal growing conditions are observed in areas with an average temperature of around 20.4°C  

## Output  
- Visualizations (matplotlib/seaborn):  
  - Bar charts: Average Yield by Year  
  - Line plots: Average Rainfall and Temperature by Year  
  - Scatter plots: Temperature vs. Predicted Yield for 2025  
  - Pie charts: Distribution of Top 5 Crop Types  
---
This work is part of my **50 Days of Python + Data Science Challenge**.  
Follow along for more projects and insights!