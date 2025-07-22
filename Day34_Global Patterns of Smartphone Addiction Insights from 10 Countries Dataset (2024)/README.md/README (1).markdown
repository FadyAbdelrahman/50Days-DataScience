# 📱 Global Patterns of Smartphone Addiction: Insights from 10 Countries (2024) - Day 34 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze smartphone addiction patterns across 10 countries to understand usage trends, demographic influences, and potential socio-economic correlations.

## Dataset  
- **Source:** Mobile Addiction Dataset (2024)  
- **Format:** CSV  
- **Features:**  
  - User_ID  
  - Country  
  - Age  
  - Gender  
  - Occupation  
  - Education_Level  
  - Income_USD  
  - Daily_Screen_Time_Hours  
  - Phone_Unlocks_Per_Day  
  - Social_Media_Usage_Hours  
  - Gaming_Usage_Hours  
  - Streaming_Usage_Hours  
  - Messaging_Usage_Hours  
  - Work_Related_Usage_Hours  
  - Sleep_Hours  
  - Physical_Activity_Hours  
  - Mental_Health_Score  
  - Depression_Score  
  - Anxiety_Score  
  - Stress_Level  
  - Relationship_Status  
  - Has_children  
  - Urban_or_Rural  
  - Time_Spent_With_Family_Hours  
  - Online_Shopping_Hours  
  - Internet_Connection_Type  
  - Primary_Device_Brand  
  - Has_Screen_Time_Management_App  
  - Self_Reported_Addiction_Level  
  - Monthly_Data_Usage_GB  
  - Has_Night_Mode_On  
  - Age_First_Phone  
  - Tech_Saviness_Score  
  - Push_Notifications_Per_Day  

## Methods  
- Cleaned data by:  
  - Handling missing values in `Education_Level` by filling with "Unknown".  
  - Ensuring all relevant columns are in numeric format for analysis.  
- Enriched data by:  
  - Grouping data by country, gender, education level, and other demographic factors.  
- Visualizations:  
  - Bar plot: Top countries by average daily screen time.  
  - Pie chart: Distribution of primary device brands.  
  - Line plot: Average screen time vs. age.  
  - Stacked bar chart: Addiction level distribution by country.  

## Key Insights  
- **Top Addicted Countries:** India and Mexico exhibit the highest average daily screen time.  
- **Demographic Trends:** Younger users and males show higher levels of smartphone addiction.  
- **Socioeconomic Influence:** Individuals with higher education levels tend to report lower addiction severity.  
- **Behavioral Patterns:** Severe addiction is linked to reduced sleep duration, and Japan has the highest social media usage.  

## Output  
- Visualizations saved for presentations and social media.  
- CSV files:  
  - `addiction_by_country.csv`: Aggregated addiction metrics by country  
  - `usage_patterns_by_demographics.csv`: Usage statistics by demographic groups  

## Next Steps  
- Develop predictive models to identify factors contributing to addiction levels.  
- Build interactive dashboards (e.g., Streamlit / Plotly Dash) to explore addiction trends dynamically.  

---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!