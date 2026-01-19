# Oil Production Performance Analysis & Dashboard

## Project Overview

This project analyzes historical oil production data to evaluate production performance, structural composition, geographic distribution, and volatility over time. The analysis was conducted using Python in Jupyter Notebook, and the insights were visualized through a multi-page interactive dashboard built with Power BI Desktop.

The goal of this project is to transform raw production data into actionable insights that support trend analysis, performance evaluation, and data-driven decision-making.

---

## Objectives

* Analyze long-term trends in oil production
* Evaluate year-on-year production changes
* Identify top-producing states and their contribution patterns
* Compare onshore and offshore production structures
* Assess production volatility across categories
* Present insights through a clear, professional Power BI dashboard

---

## Tools & Technologies

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Jupyter Notebook** for data cleaning and analysis
* **Power BI Desktop** for dashboard visualization
* **Excel / CSV** for data export and integration

---

## Data Description

The dataset contains historical oil production records with the following key fields:

* `year` – Production year
* `state` – Producing state
* `volume` – Oil production volume
* `land_category` – Onshore or Offshore production classification

---

## Data Analysis Summary

The analysis was structured into multiple stages:

### 1. Exploratory Data Analysis (EDA)

* Examined overall production levels and trends
* Identified fluctuations and long-term patterns
* Verified data consistency and completeness

### 2. Time-Series Analysis

* Computed annual oil production totals
* Calculated year-on-year percentage changes
* Removed incomplete years to ensure reliable trend comparisons

### 3. State-Level Analysis

* Identified top oil-producing states based on cumulative output
* Analyzed yearly contribution percentages by state
* Assessed shifts in production dominance over time

### 4. Production Structure Analysis

* Compared onshore and offshore production volumes
* Evaluated changes in production share across years
* Analyzed volatility to understand production stability and risk

---

## Dashboard Overview

The Power BI dashboard is organized into **three pages** for clarity and storytelling:

### Page 1: Overview

* Total oil production
* Peak production year
* Average year-on-year change
* Annual production trend
* High-level onshore vs offshore comparison

### Page 2: State Analysis

* Top 5 oil-producing states
* State contribution heatmap by year
* Production trends for dominant states

### Page 3: Production Structure & Volatility

* Onshore vs offshore production trends
* Percentage share of production by land category
* Volatility analysis across production segments

Each page includes descriptive tooltips to guide interpretation and enhance usability.

---

## Key Insights

* Oil production exhibits significant volatility across years
* Production is concentrated in a small number of states, though dominance shifts over time
* Offshore production shows higher variability compared to onshore production
* Structural composition plays a major role in overall production stability

---

## Files in This Repository

* `oil_production_performance_analysis.ipynb` – Jupyter Notebook containing data cleaning and analysis
* `oil_production_dashboard_tables.xlsx` – Exported tables used in Power BI
* `Oil_Production_Performance_Dashboard.pbix` – Power BI dashboard file
* `README.md` – Project documentation

---

## How to Use

1. Open the Jupyter Notebook to review the data analysis process
2. Load the Excel file into Power BI Desktop
3. Open the `.pbix` file to explore the interactive dashboard
---

## Author

**Alabi Oshomoshiofu Precious**
Computer Engineering Graduate | Data & Analytics Enthusiast

---

## Notes

This project demonstrates end-to-end data analysis, from raw data processing to insight-driven visualization, following best practices in data storytelling and dashboard design.
