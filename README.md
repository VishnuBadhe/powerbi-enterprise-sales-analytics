# Enterprise Sales Analytics & BI Reporting (Power BI)

## 📌 Project Overview
This project focuses on analyzing enterprise sales data using Power BI to deliver actionable business insights.  
The dashboard provides a comprehensive view of sales performance, profitability, regional trends, and KPI tracking to support data-driven decision-making.

The project demonstrates an end-to-end Business Intelligence workflow, from data modeling to interactive dashboard storytelling.

---

## 🛠️ Tools & Technologies
- Power BI (DAX, Power Query)
- SQL (Data Preparation & Validation)
- Microsoft Excel
- Data Modeling (Star Schema)

---

## 1️⃣ Data Model
![Data Model](screenshots/01_Data_Model.png)

**Key Insights:**
- Designed a structured star-schema style data model using fact and dimension tables to support scalable reporting.
- Established clear relationships between Orders, Customers, Products, Regions, and Date tables to ensure accurate aggregations.
- Optimized the model for Power BI performance and simplified DAX calculations.

---

## 2️⃣ Executive Overview
![Executive Overview](screenshots/02_Executive_Overview.png)

**Key Insights:**
- Provided a high-level snapshot of overall business performance using key metrics such as Total Sales, Total Profit, Orders, and Customers.
- Enabled quick decision-making through consolidated KPIs displayed in a single dashboard view.
- Added interactive slicers (Year, Region, Category) to allow flexible business analysis.

---

## 3️⃣ Sales & Profit Trend
![Sales Profit Trend](screenshots/03_Sales_Profit_Trend.png)

**Key Insights:**
- Analyzed year-wise sales and profit trends to identify growth patterns and performance consistency.
- Compared Actual Sales vs Target Sales to highlight gaps and achievement levels.
- Identified periods of strong performance as well as areas requiring improvement.

---

## 4️⃣ Regional Sales Analysis
![Regional Sales Analysis](screenshots/04_Regional_Sales_Analysis.png)

**Key Insights:**
- Identified top-performing regions and states based on total sales contribution.
- Highlighted geographical sales concentration to support regional strategy and market planning.
- Enabled drill-down analysis for effective regional performance comparison.

---

## 5️⃣ KPI Performance Summary
![KPI Performance Summary](screenshots/05_KPI_Performance_Summary.png)

**Key Insights:**
- Monitored critical KPIs such as Profit Margin %, Sales vs Target, and Category-wise contribution.
- Applied conditional formatting to quickly highlight underperforming and high-performing areas.
- Supported management-level performance tracking with visually intuitive indicators.

---

## 📂 Repository Structure
```text
powerbi-enterprise-sales-analytics/
│
├── README.md
├── screenshots/
│   ├── 01_Data_Model.png
│   ├── 02_Executive_Overview.png
│   ├── 03_Sales_Profit_Trend.png
│   ├── 04_Regional_Sales_Analysis.png
│   └── 05_KPI_Performance_Summary.png
│
└── data/
    ├── Global_Superstore.pbix
    └── Report_Analysis_Template.xlsx
