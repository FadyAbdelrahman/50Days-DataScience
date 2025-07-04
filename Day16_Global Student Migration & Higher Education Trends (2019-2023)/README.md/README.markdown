# 🌍 Global Student Migration & Higher Education Trends (2019-2023) - Day 16  

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)  

## Goal  
Analyze global student migration patterns and higher education trends from 2019 to 2023, focusing on student origins, destinations, scholarships, and placement outcomes to understand key drivers and outcomes of international education.  

## Dataset  
- **Source**: globalStudent_Migration_C4.csv  
- **Format**: CSV  
- **Columns**:  
  - `student_id`  
  - `origin_country`  
  - `destination_country`  
  - `destination_city`  
  - `university_name`  
  - `course_name`  
  - `field_of_study`  
  - `year_of_enrollment`  
  - `scholarship_received`  
  - `enrollment_reason`  
  - `graduation_year`  
  - `placement_status`  
  - `placement_country`  
  - `placement_company`  
  - `starting_salary_usd`  
  - `gpa_or_score`  
  - `visa_status`  
  - `post_graduation_visa`  
  - `language_proficiency_test`  
  - `test_score`  

## Methods  
- **Data Cleaning**:  
  - Filled missing values in `placement_country` and `language_proficiency_test` with "N/A" and "None", respectively.  
- **Feature Engineering**:  
  - Grouped data by country, university, and placement status.  
  - Calculated counts and averages for scholarships, placements, and salaries.  
- **Visualizations**:  
  - Bar chart: Top 10 countries attracting international students.  
  - Bar chart: Average GPA by destination country.  
  - Bar chart: Average starting salaries by placement country.  
  - Pie chart: Scholarship distribution by country of origin.  
  - Bar chart: Number of students by year of enrollment.  
  - Pie chart: Top 10 most popular destination cities.  
  - Bar chart: Most popular fields of study.  

## Key Insights  
- **Top Destinations**: The UAE leads with 538 international students, followed by the UK (526) and Germany (518).  
- **Student Origins**: Russia (532) and Germany (531) are the top countries sending students abroad.  
- **Scholarships**: Canada and Finland have the highest number of students receiving scholarships (267 and 250 "Yes" counts, respectively).  
- **Placement Success**: 50.18% of students were placed (2,509 out of 5,000), with the USA offering the highest average starting salaries (~$92,775 USD).  
- **Popular Fields**: Social Sciences (645) and Business (636) are the most pursued fields of study.  

## Output  
- Visualizations saved for:  
  - Top 10 Countries Attracting International Students  
  - Average GPA by Destination Country  
  - Average Starting Salaries by Placement Country  
  - Scholarship Distribution by Country of Origin  
  - Number of Students by Year of Enrollment  
  - Top 10 Most Popular Destination Cities  
  - Most Popular Fields of Study  
---  
Part of my **50 Days of Python + Data Science Challenge**. Follow for more!