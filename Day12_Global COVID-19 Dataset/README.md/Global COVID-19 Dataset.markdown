# 🌍 Global COVID-19 Dataset Analysis - Day 12

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Analyze global COVID-19 data to understand the pandemic's impact, including trends in cases, deaths, recoveries, and regional differences.

## Dataset  
- **Source:** country_wise_latest.csv  
- **Format:** CSV  
- **Features:**  
  - Country/Region  
  - Confirmed  
  - Deaths  
  - Recovered  
  - Active  
  - New cases  
  - New deaths  
  - New recovered  
  - Deaths / 100 Cases  
  - Recovered / 100 Cases  
  - Deaths / 100 Recovered  
  - Confirmed last week  
  - 1 week change  
  - 1 week % increase  
  - WHO Region  

## Methods  
- Cleaned data by:  
  - Removing the row for 'Israel'.  
  - Ensuring no missing values in key columns.  
- Visualizations:  
  - Bar chart: Top 10 countries by confirmed cases.  
  - Bar chart: Top 10 countries by new cases.  
  - Bar chart: Countries with zero deaths.  
  - Bar chart: Top 10 countries by mortality rate.  
  - Bar chart: Top 10 countries by recovery rate.  
  - Bar chart: Daily new cases by WHO region.  
  - Bar chart: Top 5 countries by active cases percentage.  

## Key Insights  
- **Global totals:** 16,416,500 confirmed cases, 655,562 deaths, and 9,400,954 recoveries.  
- **Mortality rate:** 3.98% globally.  
- **Recovery rate:** 57.51% globally.  
- **Top countries:** The US leads in confirmed cases (4,290,255), followed by Brazil and India.  
- **Regional patterns:** The Americas have the highest number of cases and deaths, followed by Europe and South-East Asia.  
- **Countries with zero deaths:** Several countries, including Bhutan and Cambodia, reported zero deaths despite having confirmed cases.  
- **High new cases, low deaths:** Countries like France and the Philippines reported high new cases but relatively low new deaths.  

## Output  
- Visualizations saved for:  
  - Top 10 countries by confirmed cases.  
  - Top 10 countries by new cases.  
  - Countries with zero deaths.  
  - Top 10 countries by mortality rate.  
  - Top 10 countries by recovery rate.  
  - Daily new cases by WHO region.  

## Next Steps  
- Analyze time series data to understand trends over time.  
- Investigate correlations between socio-economic factors and COVID-19 metrics.  
- Create interactive dashboards for real-time data visualization.

---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!