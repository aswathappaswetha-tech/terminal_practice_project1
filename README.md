# Terminal-Based Data Analytics Pipeline (Python & Bash)

## 📌 Project Overview (For Recruiters)

This project demonstrates how I build a **real-world, terminal-driven data analytics pipeline** using Python and Bash.

The goal is to simulate an end-to-end analytics workflow where **raw country-level socio‑economic data** is:

* extracted,
* cleaned and transformed (ETL),
* analyzed using Python,
* and exported as analytics-ready outputs for BI tools such as **Tableau or Power BI**.

This project focuses on **practical data analyst skills**, not just theory.

---

## 🧠 Problem Statement

Raw global development datasets often come in messy formats and are not directly usable for analysis or dashboards.

This project solves that problem by:

* automating data cleaning and transformation,
* generating summary statistics and visual insights,
* and producing clean CSV outputs ready for reporting and visualization.

---

## 🛠 Skills Demonstrated

* Python (Pandas, NumPy, Matplotlib)
* Bash / Shell scripting
* ETL pipeline design (Extract → Transform → Load)
* Data cleaning & preprocessing
* Exploratory Data Analysis (EDA)
* Terminal-based automation
* Analytics-ready data preparation for Tableau

---

## 📂 Project Structure

```
terminal_practice_project1/
│
├── run_analysis.sh        # One-command pipeline execution
├── etl_pipeline.py        # Data extraction, cleaning, transformation
├── analysis.py            # EDA and visualization logic
├── output/                # Cleaned datasets and plots
├── README.md
└── .gitignore
```

---

## ▶️ How to Run the Project

Clone the repository and run the pipeline from the terminal:

```bash
git clone https://github.com/aswathappaswetha-tech/terminal_practice_project1.git
cd terminal_practice_project1
bash run_analysis.sh
```

This single command:

1. Loads the raw dataset
2. Cleans and transforms the data
3. Performs analysis
4. Saves cleaned CSV files and visualizations

---

## 📊 Outputs / Results

* Cleaned, analytics-ready CSV files
* Summary statistics of socio-economic indicators
* Visualizations such as:

  * GDP vs Life Expectancy
  * Country-level comparisons
## 📈 Interactive Dashboard (Tableau)

An interactive Tableau dashboard was built using the cleaned output from this pipeline.

🔗 **View the dashboard here:**  
[Global Development & Health Insights Dashboard](https://public.tableau.com/app/profile/swetha.aswathappa/viz/project1_17660568101340/GDPLifeExpectancyChildMortalityAnalysisDashboard?publish=yes)

### Dashboard Highlights:
- GDP vs Life Expectancy analysis
- Child Mortality comparison across countries
- Health & economic development insights
- Interactive filtering by country and indicators

📌 *The dashboard uses CSV outputs generated directly from this ETL pipeline.*


---

## 🚀 Why This Project Matters

This project reflects how data analysts work in real environments:

* using the terminal,
* automating workflows,
* and preparing data for decision-making tools.

It demonstrates my ability to move from **raw data → insights → business-ready outputs**.

---

## 👩‍💻 Author

**Swetha Gowribidanur Aswathappa**
MSc Data Analytics | Python | SQL | ETL | Data Visualization
Berlin, Germany

---

## 📎 Future Improvements

* Add logging and error handling
* Parameterize input datasets
* Extend analysis with clustering or regression models
* Connect pipeline directly to Tableau extracts
