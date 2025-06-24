# ⚽ FIFA World Cup 1930-2022 - Day 6 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze FIFA World Cup data (1930-2022) to uncover trends in team performance, goals, attendance, referee statistics, and match outcomes using data visualizations.

## Dataset  
- **Source:** FIFA World Cup matches (1930-2022)  
- **Format:** CSV  
- **Features:**  
  - Teams, scores, managers, captains  
  - Venue, attendance, year, round  
  - Goals, penalties, red/yellow cards, substitutions  
  - Extra time, penalty shootouts, referees  

## Methods  
- Cleaned data: removed irrelevant columns, handled missing values.  
- Added features: derived columns for continent, decade, and goal difference.  
- Visualizations:
  - Bar plot: Most successful teams (wins & goals)
  - Line plot: Total goals per World Cup edition
  - Bar plot: Average attendance per edition
  - Bar plot: Most frequent referees
  - Pie chart: Share of matches ending in extra time / penalty shootout
  - Bar plot: Red and yellow cards distribution
  - Bar plot: Performance comparison by continent
  - Line plot: Goals by decade  

## Key Insights  
- **Top teams:** Brazil, Germany, and Argentina consistently lead in wins and goals.  
- **Goals trend:** The average goals per tournament fluctuated, with early editions having more goals on average.  
- **Attendance:** Significant growth in average attendance post-1970s, peaking in recent editions.  
- **Referees:** Certain referees appeared repeatedly in multiple editions, indicating FIFA trust.  
- **Cards:** There is a visible increase in yellow and red cards in modern tournaments.  
- **Continental performance:** European and South American teams dominate final stages.

## Output  
- All visualizations were generated using Matplotlib and Seaborn, including:
  - Goals per tournament over time
  - Attendance trends by World Cup edition
  - Referee match frequency
  - Red/yellow card distributions
  - Performance comparison by continent
- Visuals and files are ready for use in reports, presentations, and dashboards.
 

## Next Steps  
- Create interactive dashboards (e.g., with Plotly or Tableau).  
- Perform clustering to group teams by performance patterns.  
- Map host nations and match venues geographically.

---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!
