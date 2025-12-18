my first git project

# Country Data Analytics Pipeline — ETL, Reporting & Visualization

This project is a complete, automated analytics pipeline built using Python, Bash, and the terminal. It processes a global country‑level dataset, performs cleaning and transformation, generates statistical summaries, produces visualizations, and exports a dashboard‑ready dataset for Tableau.

The entire workflow runs with a single command: bash run_analysis.sh
---

## 🚀 Project Overview

This project demonstrates a professional end‑to‑end data workflow:

- Extract: Load raw Excel data  
- Transform: Clean, standardize, and enrich the dataset  
- Load: Export cleaned data for dashboards  
- Analyze: Generate summary statistics and correlations  
- Visualize: Create charts for exploratory analysis  
- Automate: Run the entire pipeline via Bash  
This mirrors real-world data engineering and analytics practices.

---
## 📂 Project Structure
Project
data - country-data.xlxs - country_cleaned.csv- 
Scripts - country_analysis.py- country_summary_report.txt
images - country_plots.py - gdpp_distribution.png -ife_expec_vs_gdpp.png -child_mort_vs_gdpp.png
Output - run_analysis.sh

---

## 🧠 ETL Pipeline Details

### 1. Extract
Loads the raw dataset from: data/Country-data.xlxs

### 2. Transform
Cleaning steps include:

- Standardizing column names  
- Removing empty rows  
- Dropping rows missing key fields  
- Converting data types  
- Creating a GDP per capita category:
  - Low  
  - Lower‑Middle  
  - Upper‑Middle  
  - High  

### 3. Load
Exports cleaned data to: output/country_data_cleaned.csv
This file is dashboard‑ready for Tableau or Power BI.

---

## 📊 Summary Report

Generated at: output/country_summary_report.txt
Includes:

- Descriptive statistics  
- Correlation between life expectancy and GDP  
- GDP category distribution  

---

## 📈 Visualizations

Saved in:output/plots/


Charts include:

- GDP per capita distribution  
- Life expectancy vs GDP  
- Child mortality vs GDP  

---

## ⚙️ How to Run the Pipeline

### 1. Activate the virtual environment : source env/Scripts/activate

### 2. Run the automated workflow : bash scripts/run_analysis.sh

### 3. View outputs : output/country_data_cleaned.csv output/country_summary_report.txt output/plots/

---

## 📊 Dashboard Integration (Tableau / Power BI)

Load this file into Tableau: output/country_data_cleaned.csv
## 📊 Tableau Dashboard

View the interactive dashboard here:  
[Global Development & Health Insights Dashboard]

Recommended visuals:

- Life expectancy vs GDP (bubble chart)  
- Child mortality vs GDP (scatter)  
- GDP category distribution (bar chart)  
- Health spending vs life expectancy  
- Imports/exports vs GDP  

---

## 👤 Author

**Swetha Gowribidanur Aswathappa**  
Berlin, Germany  
Data Analytics | Python | SQL | Visualization | ETL Pipelines





