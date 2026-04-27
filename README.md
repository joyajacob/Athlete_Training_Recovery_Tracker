
# Athlete Training Load & Recovery Dashboard

**End-to-end sports performance analytics project** designed to support data-informed decisions in high-performance sport environments 

### Project Overview
This project demonstrates a complete data analytics workflow for monitoring athlete training load, recovery, and injury risk. Key focus is calculating the **Acute:Chronic Workload Ratio (ACWR)** — a widely used metric in sports science to identify periods of potential overtraining or undertraining.

### Technologies Used
- **Python** — pandas, numpy, matplotlib, seaborn (data cleaning & analysis)
- **SQL** — SQLite (queries on training data)
- **Power BI** — interactive dashboards and visualisations
- **Git** — version control and reproducible workflow

### Dataset
- Source: [Athlete Training & Recovery Tracker Dataset (Kaggle)](https://www.kaggle.com/datasets/prince7489/athlete-training-and-recovery-tracker-dataset)
- Synthetic dataset containing daily training hours, fatigue levels, recovery index, sleep duration, nutrition score, and performance metrics.

### Key Features & Insights
- Data cleaning and feature engineering in Python
- Calculated **Acute:Chronic Workload Ratio (ACWR)** using rolling windows (7-day acute vs 28-day chronic)
- Identified high-risk periods where ACWR > 1.5 (potential overtraining risk)
- Built interactive Power BI dashboard with trends, athlete comparisons, and risk flags
- SQL queries for aggregated performance reporting

**Main Insight:**  
Developed an analytics solution that helps coaches visualise training load trends and flag athletes at risk of overtraining, supporting better periodisation and athlete management decisions.

### Repository Structure
- `data/` — raw and processed datasets
- `notebooks/` — Jupyter notebooks for exploration and ACWR calculation
- `dashboards/` — Power BI (.pbix) file
- `src/` — Python scripts (if used)

### How to Run
1. Open `notebooks/01_data_exploration_and_acwr.ipynb`
2. Run the notebook to generate processed data and insights
3. Open the Power BI file in `dashboards/` for the interactive dashboard

### Future Enhancements
- Add predictive modelling for fatigue/injury risk
- Cloud deployment (Azure/Databricks)
- Automated daily reporting

---
