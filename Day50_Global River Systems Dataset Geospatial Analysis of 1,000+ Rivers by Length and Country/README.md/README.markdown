# Global River Systems Dataset: Geospatial Analysis of 1,000+ Rivers by Length and Country - Day 50 EDA

**Date:** August 7, 2025

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Analyze a dataset of over 1,000 rivers to uncover patterns in river lengths, geographic distributions, and the countries they flow through using Python and geospatial analytics.

## Dataset  
- **Title:** Global River Systems Dataset  
- **Format:** CSV  
- **Size:** 1,387 rows × 10 columns  
- **Key Columns:**  
  - `river_name`, `river_length_km`  
  - `source_lat`, `source_lon`, `mouth_lat`, `mouth_lon`  
  - `countries_passed`, `continent`, `main_country`, `length_category`

## Methods  
- Loaded and inspected the dataset for missing values  
- Grouped data by continent, country, and length category for analysis  
- Performed geospatial analysis using Folium to map river sources and mouths  
- Created visualizations to illustrate findings, including:  
  - Bar plots for number of rivers by continent  
  - Line plots for average river length by continent  
  - Scatter plots for river length vs. number of countries passed  
  - Interactive maps for global river distribution  

## Key Insights  
- **North America** leads with 330 rivers, followed by **Europe** with 319  
- The **Lena River** is the longest at 8,546.62 km  
- Most rivers (1,106) flow through one country, while some span up to 7 countries  
- **Europe** has the highest average river length at 879.66 km  

## Output  
- Visualizations (matplotlib/seaborn/folium):  
  - Bar charts: Number of Rivers by Continent  
  - Line plots: Average River Length by Continent  
  - Scatter plots: River Length vs. Number of Countries  
  - Interactive Map: Global River Distribution  
---
This work is part of my **50 Days of Python + Data Science Challenge**.  
Follow along for more projects and insights!