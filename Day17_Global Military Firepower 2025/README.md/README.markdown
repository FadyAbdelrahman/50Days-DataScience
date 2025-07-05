# 🌍 Global Military Firepower 2025 - Day 17  

## Author  
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)  

## Goal  
Analyze global military firepower rankings for 2025, focusing on defense budgets, active personnel, equipment counts, and natural resource reserves to assess military strength across countries and regions.  

## Dataset  
- **Source**: global_military_firepower_2025.csv  
- **Format**: CSV  
- **Columns**:  
  - `rank`  
  - `country`  
  - `region`  
  - `total_population`  
  - `total_military_manpower`  
  - `fit_for_service`  
  - `population_reaching_military_age_annually`  
  - `active_personnel`  
  - `reserve_personnel`  
  - `paramilitary`  
  - `total_military_aircraft`  
  - `fighter_aircraft`  
  - `attack_aircraft`  
  - `transport_aircraft`  
  - `trainer_aircraft`  
  - `special_mission_aircraft`  
  - `tanker_aircraft`  
  - `total_military_helicopters`  
  - `attack_helicopters`  
  - `tanks`  
  - `armored_fighting_vehicles`  
  - `self_propelled_artillery`  
  - `towed_artillery`  
  - `rocket_projectors`  
  - `total_naval_fleet`  
  - `total_naval_fleet_tonnage_mt`  
  - `aircraft_carriers`  
  - `helicopter_carriers`  
  - `submarines`  
  - `destroyers`  
  - `frigates`  
  - `corvettes`  
  - `coastal_patrol_craft`  
  - `mine_warfare_craft`  
  - `defense_budget_usd`  
  - `external_debt_usd`  
  - `purchasing_power_parity_usd`  
  - `foreign_exchange_and_gold_reserves_usd`  
  - `total_serviceable_airports`  
  - `labour_force`  
  - `major_ports_and_terminals`  
  - `total_merchant_marine_fleet`  
  - `railway_coverage_km`  
  - `roadway_coverage_km`  
  - `oil_production_bbl`  
  - `oil_consumption_bbl`  
  - `proven_oil_reserves_bbl`  
  - `natural_gas_production_cum`  
  - `natural_gas_consumption_cum`  
  - `proven_natural_gas_reserves_cum`  
  - `coal_production_cum`  
  - `coal_consumption_mt`  
  - `proven_coal_reserves_cum`  
  - `total_land_area_sq_km`  
  - `coastline_coverage_km`  
  - `border_coverage_km`  
  - `waterway_coverage_km`  

## Methods  
- **Data Cleaning**:  
  - Filled missing values in `total_naval_fleet_tonnage_mt` with the mean value.  
  - Corrected typos (e.g., "filina" to "fillna").  
- **Feature Engineering**:  
  - Grouped data by region to calculate totals for active personnel, naval fleets, and defense budgets.  
  - Sorted countries by rank, defense budget, and natural resource reserves.  
- **Visualizations**:  
  - Bar chart: Top 10 countries by defense budget.  
  - Bar chart: Top 10 countries by cumulative coal production.  
  - Horizontal bar chart: Total naval vessels by region.  
  - Bar chart: Top 10 countries by proven oil reserves.  
  - Bar chart: Total active personnel by region.  

## Key Insights  
- **Top Rankings:** United States ranks 1 with a power index of 0.0712, followed by Russia (0.0798) and China (0.0821).  
- **Defense Budgets:** USA leads with $895 billion, followed by China ($266.85 billion) and Russia ($126 billion).  
- **Personnel:** China has the highest active personnel (2 million), followed by India (1.45 million).  
- **Resources:** Russia tops proven oil reserves (80 billion barrels), while China leads coal production (4.827 billion cumulative).  
- **Regional Strength:** Asia dominates with 13.35 million active personnel and $575.5 billion in defense spending.  

## Output  
- Visualizations saved for:  
  - Top 10 Countries by Defense Budget  
  - Top 10 Countries by Cumulative Coal Production  
  - Total Naval Vessels by Region  
  - Top 10 Countries by Proven Oil Reserves  
  - Total Active Personnel by Region  
---  
Part of my **50 Days of Python + Data Science Challenge**. Follow for more!