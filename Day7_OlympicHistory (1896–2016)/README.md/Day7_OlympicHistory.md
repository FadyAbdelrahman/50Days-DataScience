# 🏅 120 Years of Olympic History: Athletes and Results - Day 7

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze 120 years of Olympic Games history to uncover patterns in athlete performance, medal distributions, gender participation, and continental dominance using Python and data visualization techniques.

## Dataset  
- **Title:** 120 years of Olympic history: athletes and results  
- **Source:** [Kaggle - Sports Reference Scraped Data](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)  
- **Format:** CSV  
- **Size:** 271,116 rows × 15 columns  
- **Key Columns:**  
  - Name, Sex, Age, Height, Weight  
  - Team, NOC (Country Code), Year, Season, City  
  - Sport, Event, Medal (Gold/Silver/Bronze)

## Methods  
- Cleaned missing values in `Age`, `Height`, `Weight`, and `Medal` columns  
- Added continent classification for each NOC code (`Continent` column)  
- Performed the following analyses:

### 📊 General Analysis
- 🥇 Top medal-winning countries overall  
- 🌍 Medal counts grouped by continent  
- 👨‍🦱👩‍🦰 Gender-based medal analysis  
- 🏋️‍♂️ Top sports by participation  
- 🏙️ Host cities' frequency and performance impact  
- ☀️❄️ Comparison between Summer and Winter Games  

### 📈 Advanced Analysis  
- 📐 Average height/weight per sport  
- 🎯 Age distribution for medalists by sport  
- ⏳ Medal trends over decades  
- 🏆 Top athletes with the most medals  
- 🧭 Continental excellence by sport (e.g. Africa in athletics, Asia in weightlifting)  
- 🥇 Medal type distribution (Gold, Silver, Bronze) per continent  

## Key Insights  
- **USA** leads overall medal counts by a significant margin  
- **Europe** dominates most sports, especially swimming and gymnastics  
- **Africa** stands out in long-distance running and athletics  
- **Female participation** has grown steadily over the decades  
- **Different continents excel in different sports**, showcasing regional strengths  
- **Host cities** often experience medal boosts due to home advantage  

## Output  
- Visualizations (matplotlib/seaborn):  
  - Bar charts of medal counts by continent and sport  
  - Line plots for trend analysis over time  
  - Pie charts for gender distribution  
  - Stacked bar charts for medal type distribution  

## Next Steps  
- Explore **interactive dashboards** using Plotly/Dash  
- Add **animated visualizations** to show medal trends over time  
- Merge **economic and population data** to study correlation with Olympic success

---

This work is part of my **50 Days of Python + Data Science Challenge**.  
Follow along for more projects and insights!  
