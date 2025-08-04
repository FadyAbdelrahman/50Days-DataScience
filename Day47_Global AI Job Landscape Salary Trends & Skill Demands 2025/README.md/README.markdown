# Global AI Job Landscape: Salary Trends & Skill Demands 2025 - Day 47 EDA

**Date:** August 4, 2025

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Analyze a dataset of AI job listings to uncover salary trends and skill demands in the global AI job market for 2025.

## Dataset  
- **Title:** Global AI Job Dataset  
- **Format:** CSV  
- **Size:** 15,000 rows × 19 columns
- **Key Columns:**  
  - `job_id`, `job_title`, `salary_usd`, `salary_currency`  
  - `experience_level`, `employment_type`, `company_location`, `company_size`  
  - `employee_residence`, `remote_ratio`, `required_skills`, `education_required`  
  - `years_experience`, `industry`, `posting_date`, `application_deadline`  
  - `job_description_length`, `benefits_score`, `company_name`

## Methods  
- Cleaned the dataset by removing rows with "Israel" in `company_location` or `employee_residence`  
- Categorized job titles into groups like Engineering, Science, and Consulting  
- Performed grouping and aggregation to analyze:  
  - Average salary by experience level, employment type, and industry  
  - Number of jobs by category, industry, and company  
  - Fully remote jobs and their average salary  
  - Jobs requiring specific skills like Python  
- Created visualizations to illustrate findings, including bar plots, line plots, pie charts, and histograms  

## Key Insights  
- Switzerland leads with the highest average salary at $152,313  
- Engineering roles are the most common job category  
- Python is the most in-demand skill, appearing in 4,151 job listings  
- Fully remote jobs have an average salary of $117,465  
- Jobs requiring over 10 years of experience offer the highest salaries, averaging $174,665 for fully remote positions  

## Output  
- Visualizations (matplotlib/seaborn):  
  - Bar plots: Average Salary by Experience Level, Average Salary by Industry  
  - Line plots: Average Salary by Years of Experience  
  - Pie charts: Employment Type Distribution  
  - Histograms: Salary Distribution  
---

This work is part of my **50 Days of Python + Data Science Challenge**.  
Follow along for more projects and insights!