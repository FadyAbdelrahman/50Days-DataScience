# Spotify Global Streaming Data (2024) - Day 37 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze Spotify's global streaming data from 2024 to understand trends in music consumption, artist popularity, and user behavior across different countries and genres.

## Dataset  
- **Source:** Spotify Global Streaming Data (2024)  
- **Format:** CSV  
- **Features:**  
  - Country  
  - Artist  
  - Album  
  - Genre  
  - Release Year  
  - Total Streams (Millions)  
  - Monthly Listeners (Millions)  
  - Avg Stream Duration (Min)  
  - Skip Rate (%)  
  - Platform Type  
  - Total Hours Streamed (Millions)  
  - Streams Last 30 Days (Millions)  

## Methods  
- Cleaned data by:  
  - Handling missing values in streaming metrics.  
  - Standardizing column names for consistency.  
- Enriched data by:  
  - Grouping data by country, genre, and release year.  
- Visualizations:  
  - Bar plot: Average streams by genre.  
  - Bar plot: Total streams per country.  
  - Line plot: Average streams by release year.  
  - Heatmap: Relationship between streams and monthly listeners.  
  - Pie chart: Distribution of genres in 2024.  

## Key Insights  
- **Genre Popularity:** Classical music leads in total hours streamed, indicating its enduring appeal.  
- **User Behavior:** Over 50% of total streams come from premium users, highlighting the importance of subscription models.  
- **Regional Trends:** The United States and Brazil show significant streaming activity, with distinct genre preferences.  
- **Skip Rates:** Jazz has the highest average skip rate in the U.S., while Rock has one of the lowest.  

## Output  
- Visualizations saved for presentations and social media.  
- CSV files:  
  - `streams_by_country.csv`: Aggregated streaming metrics by country  
  - `streams_by_genre.csv`: Aggregated streaming metrics by genre  
---
This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!