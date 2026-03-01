#  Energy Consumption & Weather Data Analysis

This repository contains a time-series data analysis project focused on heat consumption and external temperature data.  
The project was initially developed as part of a recruitment process.

##  Project Objectives
The main goal of this analysis was to process raw meter readings and weather data in order to identify consumption patterns.  
Key objectives included:
1. Cleaning and preprocessing raw datasets.
2. Aggregating data into meaningful time intervals (hourly, daily, and monthly).
3. Analyzing and visualizing the relationship between average external temperature and heat consumption.

##  Tools & Technologies Used
- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:**  
  - `pandas`, `NumPy` – data manipulation and time-series aggregation  
  - `matplotlib`, `seaborn` – data visualization (including logarithmic-scale scatter plots)

##  Key Analytical Steps
- Transformation of raw timestamps into structured time intervals to calculate actual energy usage.
- Aggregation of data at multiple time resolutions to reveal seasonal and daily patterns.
- Visual analysis of how heat consumption responds to changes in external temperature.
- Export of cleaned and aggregated datasets for further reporting and analysis.

> **Note:**  
> Raw input datasets (e.g. `.xlsx` files) are intentionally excluded from this public repository due to their non-public, company-specific nature.
