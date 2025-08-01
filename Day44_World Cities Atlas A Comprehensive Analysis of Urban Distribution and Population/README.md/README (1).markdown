# 🌍 World Cities Atlas: A Comprehensive Analysis of Urban Distribution and Population - Day 44 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Analyze a dataset of world cities to uncover insights into urban distribution and population patterns across the globe.

## Dataset  
- **Title:** World Cities Atlas  
- **Source:** [Link to Dataset]  
- **Format:** CSV  
- **Size:** 47,792 rows × 11 columns  
- **Key Columns:**  
  - `city`, `city_ascii`  
  - `lat`, `lng`  
  - `country`, `iso2`, `iso3`  
  - `admin_name`, `capital`  
  - `population`, `id`

## Methods  
- Cleaned missing values in columns like `city_ascii`, `iso2`, `admin_name`, `capital`, and `population` using appropriate methods (e.g., filling `city_ascii` with `city`, using mode or mean for others)  
- Performed grouping and aggregation to analyze:  
  - Number of cities per country  
  - Average population per country  
  - Top cities by population  
  - Distribution of cities by administrative regions  
  - Geographic distribution using latitude and longitude  
- Created visualizations to illustrate findings

## Key Insights  
- **Urban Density:** India leads with the highest number of cities (7,106), followed by the United States (5,344) and Brazil (2,961)  
- **Population Giants:** Tokyo is the most populous city with over 37 million residents, followed by Jakarta and Delhi  
- **Capital Cities:** There are 251 primary capitals in the dataset  
- **Geographic Extremes:** The northernmost city is Nord, located at a latitude of 81.72°  
- **Non-Capital Cities:** The average population of non-capital cities is approximately 5,970

## Output  
- Visualizations (matplotlib/seaborn):  
  - Bar plot: Top 10 Countries by Number of Cities  
  - Line plot: Average Latitude by Country (Top 10)  
  - Pie chart: City Distribution by Top 10 Admin Regions  
  - Scatter plot: City Locations (Longitude vs Latitude)

---

This work is part of my **50 Days of Python + Data Science Challenge**.  
Follow along for more projects and insights!