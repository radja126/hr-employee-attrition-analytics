# 📊 HR Employee Attrition & Retention Analytics

An end-to-end Data Analytics project designed to uncover key drivers of employee turnover, identify high-risk segments, and provide data-driven workforce retention strategies using **MySQL**, **Python**, and **Tableau Public**.

---

## 🔗 Live Interactive Dashboard
[![Tableau Public Dashboard](https://img.shields.io/badge/Tableau_Public-View_Interactive_Dashboard-E97627?style=for-the-badge&logo=tableau&logoColor=white)](YOUR_TABLEAU_PUBLIC_DASHBOARD_URL_HERE)

---

## 📌 Executive Summary
Employee turnover significantly impacts operational stability and recruitment costs. This project analyzes **1,470 employee records** to evaluate key factors influencing attrition. The pipeline covers raw data cleaning and SQL aggregation in **MySQL**, exploratory data analysis (EDA) and segmentation in **Python**, and executive report visualization in **Tableau Public**.

### Key Business Insights
* **Overtime & Work-Life Balance:** Employees working overtime with a low work-life balance rating exhibit a critical attrition rate of **45.5%**.
* **Role & Department Vulnerability:** High turnover is heavily concentrated in entry-level positions, specifically **Sales Representatives** and **Laboratory Technicians**.
* **Tenure & Income Risk:** Significant retention risk occurs within the first **0–3 years of tenure**, combined with low monthly compensation (below $5,000).

---

## 🛠️ Tech Stack & Workflow

| Phase | Technology | Key Operations |
| :--- | :--- | :--- |
| **Data Cleaning & Storage** | MySQL | Schema design, type casting, missing value checks, SQL aggregations |
| **Exploratory Data Analysis** | Python (Pandas, Seaborn) | Statistical summary, correlation analysis, high-risk group segmentation |
| **Data Visualization** | Tableau Public | Interactive executive dashboard, KPI cards, trend & distribution charts |
| **Documentation & Hosting** | Git, GitHub, Vercel | Version control, repository documentation, portfolio embedding |

---

## 📂 Repository Structure

```text
├── data/
│   ├── raw_hr_data.csv
│   └── hr_cleaned_data.csv
├── sql/
│   ├── data_cleaning.sql
│   └── aggregation_queries.sql
├── notebooks/
│   └── hr_analytics_eda.ipynb
├── dashboard/
│   └── HR_Attrition_Dashboard.twbx
├── README.md
└── .gitignore