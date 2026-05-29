# 📊 Power BI Portfolio: E-Ticketing & User Transit Analytics
> **Project Case Study: Digital Transportation Ecosystem Integration at PT Jakarta Lingko Indonesia**

---

## 📌 Project Overview
[cite_start]This project showcases the implementation of data analytics and business intelligence to monitor and evaluate user transit behavior during the third phase of integration at PT Jakarta Lingko Indonesia[cite: 16, 17]. The primary objective was to transform fragmented, raw database logs into an interactive, actionable dashboard for strategic decision-making.

The dashboard visualizes key metrics regarding user travel patterns, e-ticketing performance, and tariff integration stability (such as the combined IDR 10,000 multi-modal tariff scheme).

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Business Intelligence:** Power BI Desktop, Power Query Editor
* **Database Management:** SQL (MySQL), phpMyAdmin
* **Data Methodology:** ETL (Extract, Transform, Load), Data Modeling (Star Schema), DAX (Data Analysis Expressions)
* **System Analysis:** Requirement Gathering, Data Validation, Functional Alignment

---

## 🚀 Key Features & Dashboards
1. **User Transit Analytics:** Monitoring peak travel hours, busiest stations/routes, and overall commuter volume trends.
2. **E-Ticketing Performance:** Real-time data validation ensuring transactional data integrity between system backend databases and frontend UI elements.
3. **Data Integrity Monitoring:** Identifying anomalies or data drop-offs in transaction logs using automated data profiling.

---

## 📈 Data Pipeline & Architecture (ETL Process)

### 1. Extract (SQL Querying)
Utilized optimized SQL queries in **phpMyAdmin** to pull transactional raw datasets, filtering relevant parameters to reduce data load and improve visualization performance.

### 2. Transform (Power Query)
* Cleaned null values and handled missing transit logs.
* Standardized date/time formats and normalized transactional variables.
* Created a central **Date Dimension Table** using DAX to support flexible time-intelligence functions.

### 3. Load & Modeling
Modeled the database structure utilizing a **Star Schema** layout, connecting Fact Tables (Transactions) with Dimension Tables (Stations, Users, Time) to optimize query performance within Power BI.

---

## 💡 Business Impact & Insights Delivered
* **Operational Efficiency:** Provided the operations team with visibility into bottleneck stations during peak hours, enabling better field resource allocation.
* **System Validation:** Acted as a bridge between System Analysts and Developers by detecting mismatch bugs between user UI inputs and database transaction receipts.
* **Data-Driven Strategy:** Supported executive stakeholders in assessing the adoption rate of multi-modal integrated ticketing cards.

---

## 📂 Repository Structure
```text
├── Data/                 # Sample anonymized datasets / Mock data (CSV/Excel)
├── Dashboards/           # .pbix Power BI project files
├── Screenshots/          # Image previews of the dashboard layout
└── README.md             # Project documentation
