# 🚢 Titanic Dataset - Day 1 EDA

## Author
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/) 

## Goal
Explore Titanic passenger data to understand survival patterns using data visualizations.

## Dataset
- Source: [Titanic dataset](https://www.kaggle.com/c/titanic/data)
- 714 passengers, 8 features (including age, sex, pclass, fare, etc.)

## Methods
- Filled missing age values with the median.
- Created visualizations:
  - Bar plot: survival rate by gender
  - Box plot: age distribution by survival
  - Count plot: survival by age group
  - Correlation matrix heatmap

## Key Insights
- **Gender:** Females had a much higher survival rate compared to males.
- **Passenger class:** Higher class passengers (1st class) had better survival odds.
- **Age:** Weak correlation with survival; survival was mixed across ages.
- **Correlation matrix:** Pclass negatively correlated with survival (-0.36).

## Output
Plots and visualizations are saved in the `output/` directory.

## Next Steps
- Build a predictive model (e.g., logistic regression) in Day 2.

---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!
