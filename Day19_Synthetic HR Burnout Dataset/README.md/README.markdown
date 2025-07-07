# 📊 Synthetic HR Burnout Dataset - Day 19 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Analyze a synthetic HR dataset on employee burnout to understand the factors contributing to burnout, such as workload, mental fatigue, and work-life balance, and their relationships with demographic variables like age and gender.

## Dataset  
- **Source:** Synthetic HR Burnout Dataset (generated to simulate real-world scenarios)  
- **Format:** CSV  
- **Features:**  
  - employee_id  
  - age  
  - gender  
  - workload  
  - mental_fatigue  
  - work_life_balance  
  - overtime_hours  
  - experience_years  
  - burnout_score  

## Methods  
- Cleaned data by:  
  - Handling missing values in `mental_fatigue` and `work_life_balance`.  
  - Normalizing `burnout_score` for consistent analysis.  
- Enriched data by:  
  - Adding `workload_intensity` as a derived feature from workload and overtime hours.  
- Visualizations:  
  - Scatter plot: Burnout score vs. mental fatigue.  
  - Bar plot: Average burnout by gender.  
  - Box plot: Burnout distribution across age groups.  
  - Heatmap: Correlation matrix of key features.  
  - Line plot: Burnout trends over experience years.  

## Key Insights  
- **Burnout and Fatigue:** Employees with mental fatigue scores above 7 show a significant increase in burnout.  
- **Workload Impact:** Higher workload and overtime hours strongly correlate with increased burnout levels.  
- **Work-Life Balance:** Better work-life balance (scores below 3) is associated with lower burnout rates.  
- **Demographic Patterns:** Age and experience show minimal correlation with burnout, while gender differences are negligible.  

## Output  
- Visualizations saved for presentations and social media.  
- CSV files:  
  - `burnout_by_age_group.csv`: Aggregated burnout metrics by age group  
  - `feature_correlation.csv`: Correlation results between features  
---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!