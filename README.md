# Global-Sales-Performance-Dashboard

# 📊 Global Superstore - Sales & Financial Performance Dashboard

An end-to-end interactive 3-page Power BI dashboard built using the *Global Superstore Dataset (Orders Analysis)*. This project transforms raw transaction logs into executive-level visual insights to monitor global profitability, regional performance, and product category distributions.

---

## 🎯 Executive Summary & Key KPIs
- *Total Revenue:* $12.64M
- *Total Profit:* $1.47M
- *Total Quantity Sold:* 178K units
- *Timeframe Analyzed:* 2012 – 2015

---

## 📁 Repository Structure
```text
├── Global_Sales_Performance_Dashboard.pbix   # Main Power BI Report File
├── Global_Superstore_Orders.xlsx            # Source Dataset (Orders Sheet)
├── Screenshots/
│   ├── 01_Overall_Sales.png                 # Executive Overview
│   ├── 02_Region_State_Analysis.png         # Geographic Breakdown
│   └── 03_Category_Analysis.png             # Product Metrics
└── README.md                                # Project Documentation


📖 Dashboard Architecture & Pages
​Page 1: Overall Sales Overview
​Core Metrics: High-level executive KPI cards for Revenue, Profit, and Quantity.
​Trend Analysis: Line and Column charts analyzing Sales and Profit trajectories across 2012–2015 quarters.
​Geographic Map: Global map visualization mapping sales distribution across continents.
​Segment Breakdown: Donut chart highlighting Consumer (51.48%), Corporate (30.25%), and Home Office (18.27%) contributions.
​Page 2: Region & State Level Analysis
​Interactive Filtering: Slicers for Region, Order Year, and State.
​Granular Table: Matrix showing city-wise sales volume and overall profit margins (e.g., NYC, LA, London).
​Comparative Visuals: Area charts for yearly regional profits and bar charts for state-level categorical distribution.
​Page 3: Category & Sub-Category Level Analysis
​Sector Deep-Dive: Interactive analysis of Technology, Office Supplies, and Furniture sectors.
​Scatter Plot & Tree Maps: Highlighting sub-category profit margins against quantity sold.
​Quarterly Trajectory: Line charts tracking profit growth across quarters per category.
​🛠️ Tools & Technical Implementation
​BI Tool: Microsoft Power BI Desktop
​Data Source: Global Superstore (Orders sheet)
​Data Modeling & Transformation: Cleaned missing values, updated data types, created custom date slicers, and developed cross-filtering page interactions.
​Visuals Used: KPI Cards, Donut Charts, Pie Charts, Scatter Plots, Tree Maps, Stacked Bar Charts, and Map Visuals.



How to Run this Project
Download or clone this repository.
Open Global_Sales_Performance_Dashboard.pbix in Power BI Desktop.
(Optional) If prompted for data source path, point it to Global_Superstore_Orders.xlsx
