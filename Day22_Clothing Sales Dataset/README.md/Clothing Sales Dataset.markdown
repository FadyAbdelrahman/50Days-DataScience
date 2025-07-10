# 👕 Clothing Sales Dataset - Day 22 EDA

## Author  
👤 **Your Name**  
[LinkedIn](https://www.linkedin.com/in/your-profile/)

## Goal  
Analyze a dataset of clothing store sales to uncover trends in sales performance, payment methods, product categories, and shopping patterns using Python and data visualization techniques.

## Dataset  
- **Title:** Clothing Sales Dataset  
- **Source:** Custom dataset (Clothing_Store_Sales_Data.csv)  
- **Format:** CSV  
- **Size:** 10,000 rows × 9 columns  
- **Key Columns:**  
  - `InvoiceNo`, `Store`, `ItemCategory`  
  - `Price`, `Quantity`, `TotalAmount`  
  - `Date`, `PaymentMethod`

## Methods  
- Cleaned data by verifying no missing values and converting `Date` to datetime format  
- Grouped data by store, product category, and date for aggregation  
- Created visualizations to explore sales trends and relationships  
- Performed the following analyses:

### 📊 General Analysis  
- Total sales and quantity sold by store  
- Distribution of payment methods  
- Top-selling product categories by total sales  
- Sales trends by day of the week  
- Top invoices by quantity sold  

### 📈 Advanced Analysis  
- Heatmap of price vs. quantity impact on total sales  
- Average price and total amount by product category  
- Percentage distribution of payment methods  
- Sales aggregation by date and store  

## Key Insights  
- **Top Stores:** Store A leads with $893,812.07 in sales, followed by Store B ($884,349.56) and Store C ($880,232.57).  
- **Payment Methods:** Credit Card (25.41%) and Online Payment (25.23%) are slightly more popular than Debit Card (24.88%) and Cash (24.48%).  
- **Product Categories:** Jeans ($449,885.83) and T-shirts ($449,062.75) dominate sales.  
- **Sales by Day:** Sundays ($392,506.13) and Saturdays ($390,386.74) are peak days; Mondays ($359,305.43) are the slowest.  
- **Invoice Highlight:** Invoice INVO1953 had the highest quantity sold (39 units).  

## Output  
- Visualizations (matplotlib/seaborn):  
  - Bar charts for total sales by category  
  - Pie chart for payment method distribution  
  - Heatmap for price vs. quantity  
  - Sales by day of the week  
  - Top 5 invoices by quantity sold  

---

This work is part of my **50 Days of Python + Data Science Challenge**.  
Follow along for more projects and insights!