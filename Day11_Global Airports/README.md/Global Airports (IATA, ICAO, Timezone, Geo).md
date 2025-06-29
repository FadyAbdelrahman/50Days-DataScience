# 🌍 Global Airports (IATA, ICAO, Timezone, Geo) - Day 10 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze a comprehensive dataset of global airports to uncover patterns in airport distribution, timezone variations, geographic coordinates, and identification codes using Python and visual analytics.

## Dataset  
- **Title:** Global Airports (IATA, ICAO, Timezone, Geo)  
- **Source:** [Custom Dataset](https://www.kaggle.com/datasets/samvelkoch/global-airports-iata-icao-timezone-geo?resource=download)  
- **Format:** CSV  
- **Size:** 6,273 rows × 13 columns (after cleaning)  
- **Key Columns:**  
  - `airportname`, `iata`, `icao`  
  - `city_name`, `city_iata`, `country_codea2`, `country_codea3`, `country_name`  
  - `geopointlat`, `geopointlong`  
  - `timezone`, `utc_offset_hours`, `utc_offset_seconds`

## Methods  
- Cleaned missing values by removing rows with missing `GeoPointLat`, `GeoPointLong`, `IATA`, `TimeZone`, and `ICAO`  
- Removed duplicates based on `AirportName`, `GeoPointLat`, and `GeoPointLong`  
- Standardized column names to lowercase with underscores  
- Filled missing `city_iata` values with `iata`  
- Performed the following analyses:

### General Analysis  
- Top 10 countries by number of airports  
- Cities with multiple airports  
- Top 10 timezones by number of airports  
- Distribution of airports by UTC offset  
- Countries with the highest geographic variance of airports  
- Average UTC offset by country  
- Geographical distribution of airports (top 10 countries)

### Advanced Analysis  
- Identification of duplicated ICAO codes  
- Relationship between UTC offset and longitude  
- Range of latitude and longitude coordinates  
- Average geographic coordinates by country

## Key Insights  
- **United States of America** leads with 1,062 airports  
- **Chicago, Illinois** and **London** have the highest number of airports per city (8 and 7 respectively)  
- **America/New_York** is the most common timezone with 292 airports  
- **UTC offsets** are most concentrated between -5 and +2 hours  
- **Lesotho** and **Swaziland** show the highest geographic variance in airport locations  
- **Duplicated ICAO codes** (e.g., `EDDB`, `EDLW`) indicate potential data quality issues  
- **Samoa** and **Tonga** have the highest average UTC offset (+13 hours)

## Output  
- Visualizations (matplotlib/seaborn):  
  - Bar charts for top 10 countries, cities, timezones, and UTC offsets  
  - Scatter plots for geographical distribution and UTC offset vs. longitude  

---

This work is part of my **50 Days of Python + Data Science Challenge**.  
Follow along for more projects and insights!