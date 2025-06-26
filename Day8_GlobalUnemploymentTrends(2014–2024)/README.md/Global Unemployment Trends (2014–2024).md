# 📊 Global Unemployment Trends (2014–2024)  - Day 8 of 50

## 👤 Author
**Fady Abdelrahman**  
🔗 [LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

---

##  Goal
Analyze global unemployment trends over the past decade across different:
- Regions (continents)
- Genders (male vs female)
- Age groups (youth, adults, children)
- Time periods (with special focus on COVID years 2020–2023)
- Predict 2025 unemployment using machine learning

---

##  Dataset
- **Name:** Global Unemployment by Country, Gender, Age, and Year
- **Years Covered:** 2014–2024
- **Features:**
  - `country_name`, `sex`, `age_group`, `age_categories`
  - Unemployment rates for each year from 2014 to 2024

---

## Methods
- **Data Cleaning**
  - Handled missing values in 2022–2024
  - Added a `continent` column (manual mapping based on country)
- **Data Reshaping**
  - Used `.melt()` to reshape for visualization
- **Visualization & Analysis**
  - Line charts, box plots, bar plots
  - Regional comparisons, age/gender breakdowns
- **Machine Learning**
  - Trained a `LinearRegression` model to predict 2025 rates
- **Clustering**
  - KMeans used to group countries based on unemployment patterns

---

## Key Insights
- **Youth have the highest unemployment rates** globally in most countries.
- **Africa and Arab countries** show consistently higher rates than global averages.
- **COVID-19** led to major spikes in 2020–2022 globally.
- **Gender gap** is significant in several regions (especially MENA).
- **Predicted 2025 rates** show sustained challenges in certain economies.
- **Clustering** revealed 4 clear unemployment patterns across the world.

---

## Visuals Included
- Unemployment by Continent (2020–2023)
- Top & Bottom 10 Countries by 2023 Rate
- Gender Gap in Unemployment (2024)
- Predicted Top/Bottom 10 Countries in 2025
- KMeans Clusters of Countries

---

## Next Steps
- Include **education level** or **GDP** data for richer insights.
- Train more robust ML models like `RandomForest`, `XGBoost`.
- Build **interactive dashboard** using `Plotly` or `Streamlit`.
- Visualize unemployment on a **world map (choropleth)**.

---

---

📌 This project is part of my **#50DaysOfPython & Data Science Challenge**  
📢 Feel free to connect and follow for daily EDA, ML & Viz challenges!

---

### 🏷️ Hashtags  
`#Python` `#DataScience` `#Unemployment` `#EDA` `#ML` `#Matplotlib` `#Pandas` `#50DaysChallenge` `#GlobalTrends` `#KaggleDatasets` `#Regression` `#Visualization` `#LinkedInChallenge`
