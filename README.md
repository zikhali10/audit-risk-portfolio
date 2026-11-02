# Audit Risk Portfolio & Executive Dashboard 📊🛡️

An enterprise-grade internal audit and risk analytics dashboard built in Power BI, designed to monitor transactional anomaly exceptions, quantify high-risk financial exposure across organizational departments, and surface critical control failures (such as duplicate payments and unauthorized weekend transactions).

## 🚀 Project Overview
In modern internal audit and statutory compliance, manual sampling leaves significant blind spots across general ledgers and procurement spend. 

The **Audit Risk Portfolio** dashboard bridges data engineering and risk assurance by automatically aggregating transactions, classifying them into risk tiers, and displaying high-risk financial exposure via an interactive executive summary. It provides audit committees and financial controllers with an immediate view of risk concentrations by department and vendor.

---

## 🛠️ Tech Stack & Architecture
* **Microsoft Power BI Desktop:** Core visualization, DAX measures, data modeling, and interactive filtering.
* **Power Query / Data Transformation:** Ingests and cleans transactional data, establishing relational schema connections between departments, vendors, and risk scores.
* **Data Modeling:** Features executive summary cards, dynamic donut charts, and granular drill-through capabilities.

---

## 📊 Core Dashboard Features
* **Executive Risk Cards:** Real-time visibility into Total Transactions, High-Risk Exposure, and overall Exception Rates.
* **Risk Score Breakdown (Donut Chart):** Visualizes the proportion of Low, Medium, and High-risk transactions.
* **Departmental Risk Exposure:** Horizontal bar chart comparing financial exposure and transaction volume across organizational departments.
* **Granular Audit Transaction Grid:** A detailed data table featuring transaction IDs, calendar timelines, vendor metadata, risk scoring, and explicit audit flags (e.g., *Duplicate Payment Indicator*, *Weekend Transaction*).

---

## 🚀 How to Explore
1. Clone or download this repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. Interact with the slicers and department bars to filter risk exposure dynamically across the audit portfolio!
