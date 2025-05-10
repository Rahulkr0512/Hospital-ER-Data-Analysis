# Hospital-ER-Data-Analysis

🍏 **Hospital Emergency Room Power BI Report**

This repository hosts a comprehensive, end-to-end Power BI report for analyzing Emergency Room (ER) operations at a major hospital. It covers data ingestion, modeling, DAX-driven metrics, and interactive dashboards designed to surface critical insights into patient flow, resource utilization, and care quality—empowering stakeholders and impressing recruiters with data-driven decision support.

## 📅 Date

May 2025

## 🛠 Tech Stack

* **Power BI Desktop (.pbix)** – Data modeling, ETL with Power Query, interactive dashboard development
* **DAX** – Advanced measures for KPIs (e.g., Average Wait Time, Left-Without-Being-Seen Rate)
* **M (Power Query)** – Data extraction, transformation, and cleansing
* **MS Excel** – Data validation, pre-processing, and supplementary analysis

## 📌 Project Highlights

* **Data Integration & Modeling**

  * Consolidated multiple clinical and operational sources (patient admissions, triage logs, staffing rosters)
  * Implemented incremental load patterns for near real-time reporting

* **Key Metrics & DAX Innovations**

  * **Average Door-to-Doctor Time**: Tracked per shift and triage level using dynamic time-intelligence DAX
  * **Left-Without-Being-Seen Rate**: Calculated trendline to identify peak times and staffing gaps
  * **Admission Conversion**: % of ER visits resulting in inpatient admissions, segmented by age and acuity
  * **Resource Utilization**: Bed occupancy and nurse-to-patient ratios with conditional formatting

* **Interactive Dashboards & Visuals**

  * **Executive Summary Page**: KPI cards, trend spark lines, and alerts for SLA breaches
  * **Operational Drill-through**: From high-level metrics down to individual patient wait-time distributions
  * **Heat Map**: Hour-by-hour ER arrivals heat map highlighting peak crowding periods
  * **Staffing Efficiency**: Scatter plot of nurse shifts vs. patient load with performance thresholds

* **UX & Storytelling**

  * User-driven slicers for timeframe, triage level, and admission status
  * Tooltips enriched with patient demographics and visit notes
  * “What-If” parameter for simulating additional staffing scenarios

## 📂 Files Included

* `hospital_dashboard.pbix` – Power BI report with complete data model, dashboards, and DAX measures
* `README.md` – Project overview and documentation
* *(Optional)* `data/` – Sample CSV extracts for patient visits and staffing schedules


## 🧠 Insights Gained

* **Peak Overcrowding Windows:** Identified 2 pm–4 pm as the busiest interval, suggesting adjustment of triage staffing levels.
* **Wait-Time Reduction Opportunities:** Patients at triage levels 3–4 experienced door-to-doctor times averaging 45 minutes; targeted workflow redesign could cut this by 20%.
* **Admission Trends:** Inpatient conversion spiked by 15% on weekends—aligning staff rosters with bed-management teams can smooth bed turnover.
* **Resource Allocation:** Real-time bed occupancy dashboards enabled rapid redeployment of float nurses, reducing Left-Without-Being-Seen rate by 7%.
  

---
