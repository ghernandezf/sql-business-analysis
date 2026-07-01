# 🛒 MercadoLibre Funnel & Retention Analysis

## 📌 Project Overview

Understanding where users abandon the purchase journey and how well they return over time is essential for improving product performance and business growth.

This project analyzes user behavior throughout MercadoLibre's conversion funnel and evaluates customer retention using SQL. By combining funnel analysis and cohort retention techniques, the project identifies key drop-off points and opportunities to improve the user experience.

---

## 🎯 Business Objective

The objective of this project is to analyze user conversion and retention in an e-commerce environment by:

* Building a complete conversion funnel from first visit to purchase.
* Measuring conversion rates between each stage of the customer journey.
* Identifying the stages with the highest user drop-off.
* Comparing funnel performance across different countries.
* Evaluating user retention through cohort analysis.
* Generating actionable business recommendations to improve conversion and long-term engagement.

---

## 📊 Business Questions

This analysis answers the following questions:

* Where do most users abandon the purchasing process?
* Which stage of the funnel has the largest conversion loss?
* How does conversion performance vary by country?
* How well are users retained after signing up?
* How do retention rates evolve over time (Day 7, Day 14, Day 21, and Day 28)?

---

## 🗄️ Dataset

The project uses two datasets:

* **mercadolibre_funnel** – User events generated throughout the purchase journey.
* **mercadolibre_retention** – User activity records used to measure retention over time.

---

## 🛠️ Tools & Technologies

* SQL
* PostgreSQL
* Common Table Expressions (CTEs)
* Aggregate Functions
* Joins
* Conditional Logic
* Date Functions

---

## 💡 SQL Techniques Demonstrated

* Common Table Expressions (CTEs)
* LEFT JOIN
* COUNT(DISTINCT)
* CASE WHEN
* GROUP BY
* ORDER BY
* ROUND()
* NULLIF()
* DATE_TRUNC()
* TO_CHAR()

---

## 📂 Repository Structure

```text
mercadolibre-funnel-retention-analysis/
│
├── README.md
├── sql/
│   ├── 01_build_conversion_funnel.sql
│   ├── 02_calculate_conversion_rates.sql
│   ├── 03_country_funnel_analysis.sql
│   ├── 04_retention_counts.sql
│   ├── 05_retention_rates.sql
│   ├── 06_create_user_cohorts.sql
│   └── 07_cohort_retention_analysis.sql
│
└── data/
    └── README.md

```

---

## 📈 Key Skills Demonstrated

* Product Analytics
* Funnel Analysis
* Cohort Analysis
* Customer Retention
* Conversion Rate Analysis
* SQL Query Optimization
* Business Metrics
* Data-Driven Decision Making

---

## 🚀 Business Value

The insights generated through this analysis help identify where users abandon the purchasing process and how retention changes over time. These findings can support product teams in prioritizing improvements that increase conversion rates, enhance customer engagement, and drive long-term business growth.

---

## 👤 Author

**Gabriel Hernández**

**Aspiring Data Analyst**

**Skills:** SQL | Python | Data Analysis | Power BI | Exploratory Data Analysis (EDA) | KPI Monitoring | Lean Six Sigma
