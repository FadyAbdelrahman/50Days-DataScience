# 🌍 World Bank Country Metadata - Day 2 EDA

## Author
👤 **Fady Abdelrahman**  
[LinkedIn](https://www.linkedin.com/in/fady-abdelrahman-a649a12b6/)

## Goal
Explore World Bank country metadata to understand the distribution of countries by region and income group using data visualizations.

## Dataset
- Source: [World Bank Metadata](https://databankfiles.worldbank.org/public/ddpext_download/UNDPAPI/UNDPAPI_SL.UEM.TOTL.ZS_DS2_en_csv_v2_80923.zip)
- 265 countries/regions, with features including:
  - Country Code
  - Region
  - Income Group
  - Special Notes
  - Table Name

## Methods
- Cleaned and explored metadata.
- Created visualizations:
  - Bar plot: number of countries by income group
  - Horizontal bar plot: number of countries by region
  - Pivot table: cross-tab of region vs. income group

## Key Insights
- **Income Group:** Most countries fall under high-income or upper-middle-income groups.
- **Region:** Europe & Central Asia and Sub-Saharan Africa have the highest number of countries.
- **Region vs. Income Group:** Pivot analysis reveals regional income patterns (e.g., Sub-Saharan Africa has many low-income countries).

## Output
Plots and visualizations are saved in the `output/` directory.

## Next Steps
- Combine metadata with unemployment data or other indicators for deeper insights.

---

This work is part of my **50 Days of Python + Data Science Challenge**. Follow me for daily projects!
