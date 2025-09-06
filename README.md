# Vaccination-Data-Analysis-and-Visualization

This project focuses on analyzing **global vaccination coverage, disease incidence, and regional disparities** using a combination of **data engineering, exploratory data analysis (EDA), and business intelligence dashboards**.

---

##  Project Overview
The goal of this project is to:
- Store vaccination and disease data in a **normalized relational database** (SQLite).
- Ensure **data integrity** with a **star schema** (fact and dimension tables).
- Perform **EDA** to identify vaccination patterns, highlight low-coverage areas, and assess vaccine impact on disease reduction.
- Build **interactive dashboards in Power BI** for health monitoring and policymaking.

---

##  Data Engineering
- Extracted and cleaned data from:
  - Vaccination schedules
  - Vaccine introductions
  - Reported cases
  - Incidence rates
  - Coverage statistics
- Designed a **star schema**:
  - **Dimensions**: Countries, Vaccines, Diseases, Years
  - **Facts**: Coverage, Cases, Incidence, Introduction, Schedule
- Enforced **primary & foreign keys** for referential integrity.

---

##  Exploratory Data Analysis (EDA)
Performed using **Python (Pandas, Matplotlib)**:
- **Statistical Summaries** of coverage %, incidence rates, and reported cases.
- **Trend Analysis**:
  - Coverage % over years
  - Disease incidence rates over time
- **Regional Disparities**:
  - WHO region-level coverage comparison
- **Correlation Analysis**:
  - Vaccination coverage vs. disease incidence

---

##  Power BI Dashboards
Built **interactive visualizations** including:
- **KPI Cards**: Global Avg Coverage %, Total Cases, Vaccines Introduced
- **Line Charts**: Coverage trends by vaccine, incidence trends by disease
- **Geographical Maps**: Coverage heatmaps across countries/regions
- **Scatter Plots**: Correlation between vaccination coverage and incidence

 Includes **slicers** for Year, Country, Vaccine, and Disease for flexible exploration.

---

##  Tools & Technologies
- **SQLite** → Data warehousing & schema design
- **Python** → Data processing, EDA
- **Power BI** → Dashboards & visualization
- **Pandas, Matplotlib** → Statistical analysis & charts

---

##  Key Insights
- Identified countries/regions with **low vaccination coverage**.
- Highlighted **outbreak years** with high disease incidence.
- Found a **negative correlation** between higher vaccination coverage and lower disease incidence.
- Demonstrated the role of **data-driven monitoring** in global health.

---
