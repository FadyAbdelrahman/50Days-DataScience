#Mapping Global Displacement: A Data-Driven Analysis of Refugees and Asylum Seekers (2019–2024) - Day 48 EDA

**Date:** August 5, 2025

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze a comprehensive dataset of global displacement data from 2019 to 2024 to uncover patterns in refugee and asylum seeker movements, using Python and visual analytics.

## Dataset  
- **Title:** Global Displacement Dataset (2019–2024)   
- **Format:** CSV  
- **Size:** 34,600 rows × 12 columns  
- **Key Columns:**  
  - `Year`, `Country of origin`, `Country of asylum`  
  - `Refugees under UNHCR's mandate`, `Asylum-seekers`, `Returned refugees`  
  - `IDPs of concern to UNHCR`, `Returned IDPs`, `Stateless persons`  
  - `Others of concern`, `Other people in need of international protection`, `Host Community`

## Methods  
- Cleaned missing values in `Other people in need of international protection` by filling with 0  
- Performed grouping and aggregation to analyze:  
  - Total refugees by country of asylum and year  
  - Average asylum seekers by country of origin  
  - Top countries by refugee hosting and asylum seekers  
  - Trends in internally displaced persons (IDPs) and returned refugees  
- Created visualizations to illustrate findings, including bar plots, pie charts, and line plots  

## Key Insights  
- Uganda leads with over 12.7 million refugees under UNHCR's mandate, followed by Chad and the Russian Federation  
- Afghanistan has the highest average number of asylum seekers per year, with over 2,790  
- Sudan recorded the highest number of returned refugees, with over 757,925 individuals  
- The number of stateless persons peaked in 2022 at over 44 million  
- 36 countries reported internally displaced persons (IDPs) under UNHCR's concern in 2023  

## Output  
- Visualizations (matplotlib/seaborn):  
  - Bar plots: Total Refugees by Year  
  - Pie charts: Top 7 Refugee-Hosting Countries in 2024  
  - Line plots: Total Asylum-Seekers by Year  
  - Area plot: Refugees, IDPs, and Returned Refugees by Year  
---

This work is part of my **50 Days of Python + Data Science Challenge**.Follow along for more projects and insights!