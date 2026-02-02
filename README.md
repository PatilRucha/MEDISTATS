# MEDISTATS  
### Pharmaceutical Drug Sales Analytics Dashboard

<img width="1136" height="643" alt="Screenshot 2026-02-01 191758" src="https://github.com/user-attachments/assets/d7d8fabb-c699-45ee-a55a-039fa663497d" />

## Overview
MediStats is an end-to-end data analytics project focused on analyzing pharmaceutical drug sales across multiple time granularities. The project demonstrates how raw, unstructured sales data can be cleaned, modeled, and transformed into meaningful business insights using Python and Power BI.
The analysis spans **daily, weekly, monthly, and hourly sales data** and enables interactive exploration of drug category performance, time-based trends, and aggregated sales metrics.


## Project Objectives
- Clean and standardize raw pharmaceutical sales datasets
- Prepare analytics-ready datasets using Python
- Design a consistent time-based data model
- Build an interactive Power BI dashboard for sales analysis
- Replace spreadsheet-based reporting with scalable BI visuals


## Tools & Technologies
- **Python** (Pandas, NumPy) – Data cleaning and preprocessing  
- **Jupyter Notebook** – Data exploration and transformation  
- **Power BI** – Data modeling, DAX calculations, and visualization  
- **DAX** – KPI and aggregation logic  


## Repository Contents

### Data Files
**Raw (Unprocessed) Data**
- `raw_salesdaily.csv`
- `raw_salesweekly.csv`
- `raw_salesmonthly.csv`
- `raw_saleshourly.csv`

These files represent the original datasets and contain inconsistent date formats, duplicates, and schema variations.

**Cleaned Data**
- `Sales Daily_clean.csv`
- `Sales Weekly_clean.csv`
- `Sales Monthly_clean.csv`
- `Sales Hourly_clean.csv`

The cleaned datasets have standardized date fields, removed duplicates, and consistent schemas suitable for analysis and visualization.


### Data Cleaning
- `Data_Cleaning.ipynb`

This notebook documents the preprocessing steps applied to all four datasets, including:
- Date parsing and format normalization
- Removal of duplicate and invalid records
- Schema alignment across datasets
- Preparation of final cleaned CSV files


### Power BI Dashboard
- `MediStats - Pharmaceutical Drug Sales Analytics.pbix`

The Power BI dashboard includes:
- KPI cards for Total Monthly Sales, Average Monthly Sales, Daily Sales, and Weekly Sales
- Drug category-wise comparisons
- Time-series analysis across years, quarters, and months
- Interactive slicers driven by a centralized date dimension


### Project Report
- `MediStats_Report.pdf`

The report provides a detailed explanation of:
- Data collection and preprocessing
- Data modeling and relationships
- DAX formulas and calculations
- Dashboard design and visual interpretation
- Conclusions, limitations, and future scope


## How to Use
1. Review raw and cleaned CSV files to understand data transformations
2. Open `Data_Cleaning.ipynb` to explore preprocessing logic
3. Open the `.pbix` file in Power BI Desktop to interact with the dashboard
4. Refer to the PDF report for complete project documentation


## Author
**Ruchira Patil**


## Notes
This project was developed for academic and learning purposes. The dataset used is publicly available and serves as a reference for analytics and visualization techniques.

