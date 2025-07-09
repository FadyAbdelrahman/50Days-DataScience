# 🌍 Global Cancer Patients (2015-2024) - Day 21 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze global cancer patient data from 2015 to 2024 to understand trends in cancer types, patient demographics, treatment costs, and survival rates across different regions and years using Python and visual analytics.

## Dataset  
- **Title:** Global Cancer Patients (2015-2024)  
- **Source:** [Synthetic Dataset]  
- **Format:** CSV  
- **Size:** 50,000 rows × 15 columns  
- **Key Columns:**  
  - `Patient_ID`, `Age`, `Gender`, `Country_Region`, `Year`  
  - `Genetic_Risk`, `Air_Pollution`, `Alcohol_Use`, `Smoking`, `Obesity_Level`  
  - `Cancer_Type`, `Cancer_Stage`, `Treatment_Cost_USD`, `Survival_Years`, `Target_Severity_Score`  

## Methods  
- **Cleaned data by:**  
  - Checking for missing values (none found).  
  - Ensuring data consistency across columns.  
- **Enriched data by:**  
  - Grouping by cancer type, country, and year for aggregated insights.  
  - Creating age bins for demographic analysis.  
- **Performed the following analyses:**  
  - Average patient age by cancer type.  
  - Patient count by cancer type and age group.  
  - Average treatment cost by cancer stage and year.  
  - Survival years by cancer stage and country.  
  - Severity score by smoking status and air pollution levels.  

### 📊 General Analysis  
- Top cancer types by patient count.  
- Distribution of cancer stages across types.  
- Average treatment costs over the years.  
- Patient demographics (age, gender) by cancer type.  

### 📈 Advanced Analysis  
- Correlation between genetic risk and severity score.  
- Impact of lifestyle factors (smoking, alcohol use, air pollution) on survival years and severity.  
- Regional differences in cancer prevalence and treatment costs.  
- Trends in cancer incidence and survival rates over time.  

## Key Insights  
- **Cancer Trends:** Colon (6,376 cases) and prostate (6,308 cases) cancers are the most common, with lung cancer showing the highest average treatment cost ($53,130 USD).  
- **Age Patterns:** Most patients fall between 50–70 years (14,116 cases), followed by 70–100 (13,582 cases).  
- **Treatment Costs:** Costs remain stable across stages (~$52,000–$52,700 USD) with slight yearly fluctuations (e.g., $52,115 in 2023, $52,796 in 2024).  
- **Survival Rates:** Survival years average ~5 years across all stages, with minor variations (e.g., Stage IV: 4.97 years).  
- **Lifestyle Impact:** Smoking and air pollution significantly increase severity scores, especially for lung cancer (e.g., severity rises from 3.94 at 0.0 smoking to 4.43 at 0.1).  

## Output  
- **Visualizations (matplotlib/seaborn):**  
  - Bar charts for patient counts by age group and treatment costs by stage.  
  - Line plots for cost trends over time.  
  - Stacked bar charts for cancer type frequency by age group.  
  ---

This work is part of my **50 Days of Python + Data Science Challenge**.  
Follow along for more projects and insights!