# ✈️ Passenger Behavior And Booking Trends In The Airline Industry - Day 46 EDA

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal  
Analyze a dataset of airline customer bookings to uncover insights into passenger behavior and booking trends.

## Dataset  
- **Title:** Airlines Customer Booking Dataset  
- **Source:** [Insert dataset source link]  
- **Format:** CSV  
- **Size:** 50,000 rows × 14 columns  
- **Key Columns:**  
  - `num_passengers`, `sales_channel`, `trip_type`  
  - `purchase_lead`, `length_of_stay`, `flight_hour`, `flight_day`  
  - `route`, `booking_origin`  
  - `wants_extra_baggage`, `wants_preferred_seat`, `wants_in_flight_meals`  
  - `flight_duration`, `booking_complete`

## Methods  
- Loaded the dataset and checked for missing values (none found)  
- Performed grouping and aggregation to analyze:  
  - Bookings by sales channel and trip type  
  - Top routes and booking origins  
  - Passenger preferences for extra baggage, preferred seats, and in-flight meals  
- Created visualizations to illustrate findings, including:  
  - Bar plots for bookings by sales channel and average length of stay by trip type  
  - Violin plots for flight duration by booking completion  
  - Scatter plots for purchase lead vs. length of stay  

## Key Insights  
- Internet bookings dominated with 44,382 bookings, while mobile bookings accounted for 5,618  
- The most booked route was AKLKUL with 2,680 bookings  
- Out of 50,000 bookings, 7,478 were completed, indicating a completion rate of approximately 15%  
- 33,439 bookings included extra baggage, and 21,357 requested in-flight meals  

## Output  
- Visualizations (matplotlib/seaborn):  
  - Bar plot: Bookings by Sales Channel  
  - Violin plot: Flight Duration by Booking Completion  
  - Scatter plot: Purchase Lead vs. Length of Stay  
  - Line plot: Average Flight Duration by Hour  

---

This work is part of my **50 Days of Python + Data Science Challenge**.  
Follow along for more projects and insights!