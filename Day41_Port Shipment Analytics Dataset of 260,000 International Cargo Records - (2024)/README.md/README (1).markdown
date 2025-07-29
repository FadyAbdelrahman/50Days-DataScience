# 🌍 Port Shipment Analytics Dataset of 260,000 International Cargo Records - (2024) - Day 41 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Explore and analyze a dataset of 260,000 international cargo records from 2024 to understand shipment trends, weight distributions, pricing patterns, and port-specific insights.

## Dataset  
- **Source:** Port Shipment Analytics Dataset (2024)  
- **Format:** CSV  
- **Features:**  
  - name  
  - price ($)  
  - weight (kg)  
  - length (m)  
  - width (m)  
  - height (m)  
  - shipment date  
  - destination port  

## Methods  
- Cleaned data by:  
  - Handling missing values with median and mode imputation.  
  - Standardizing date formats.  
- Enriched data by:  
  - Calculating volume (length * width * height).  
  - Grouping by destination port and product name.  
- Visualizations:  
  - Bar plot: Average weight by destination port.  
  - Line plot: Daily shipment prices in March 2023.  
  - Scatter plot: Price vs. weight.  
  - Box plot: Weight distribution by top ports.  

## Key Insights  
- **Port Dominance:** Port of Busan (South Korea) leads with 531,157 shipments.  
- **Weight Trends:** Average shipment weight in 2023 was 324.17 kg.  
- **Price Peaks:** Sports Cars reached a maximum price of $1,990,706.53.  
- **Economic Impact:** Port of Tianjin (China) recorded the highest total shipment costs at $246,683,700.  

## Output  
- Visualizations saved for presentations and social media.  
- CSV files:  
  - `avg_weight_by_port.csv`: Average weight by destination port  
  - `total_cost_by_port.csv`: Total shipment costs by port  
---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!