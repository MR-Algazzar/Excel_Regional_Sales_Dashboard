# 📊 Excel Regional Sales Dashboard

## 📌 Project Overview
This project delivers an interactive sales analytics and business intelligence dashboard built in **Microsoft Excel**. It transforms raw transactional sales data into a clean, structured, and dynamic executive reporting tool. The dashboard is designed to provide stakeholders with visibility into revenue generation, profitability, regional sales performance, product category contributions, customer demographics, and monthly sales trends.

> **Dashboard Preview:**
> <img width="1015" height="548" alt="Excel Regional Sales Dashboard" src="https://github.com/user-attachments/assets/978c3e57-7ceb-4cde-9e6e-51e1c09d0820" />
> *(Description: Screenshot of the interactive Excel dashboard featuring executive KPI cards, regional and category performance charts, monthly sales trends, and interactive slicers).*

---

## 🗂️ Workbook Architecture
The Excel workbook (`Excel_Regional_Sales_Dashboard.xlsx`) is structured into three main analytical worksheets:

1. **Data Source / Raw Data**: Contains the cleaned transactional sales database, capturing order IDs, transaction dates, customer details, product categories, quantities, unit prices, revenues, and profit margins.
2. **Pivot Cache / Calculations**: The backend calculation layer featuring intermediate summary tables and Pivot Table aggregations powering the dashboard metrics and visualizations.
3. **Dashboard**: The front-end executive view featuring KPI summary cards, regional and category performance charts, monthly sales trends, and interactive slicers.

---

## 🔄 Data Cleaning & Transformation Pipeline
Before building any dashboard visuals or analytical summaries, the transactional sales data underwent a structured cleaning and preparation workflow:

- **Deduplication:** Removed duplicate records to maintain data integrity and ensure consistent sales reporting.
- **Missing Value Handling:** Addressed missing values to improve data consistency and reliability during analysis.
- **Date Standardization:** Standardized date formats to support accurate chronological analysis and monthly sales trend reporting.
- **Data Structuring:** Organized the transactional data into structured tables to support efficient data retrieval and analytical operations.
- **Formula-Based Data Retrieval:** Applied lookup functions such as `XLOOKUP` and `VLOOKUP` for cross-sheet data retrieval.
- **Conditional Aggregation:** Used `SUMIFS`, `AVERAGEIFS`, and `COUNTIFS` to perform conditional calculations across different sales dimensions.

---

## 📊 Key Metrics & Executive Insights (KPIs)
The dashboard tracks 4 core performance indicators to provide a consolidated overview of overall sales performance:

- **Total Revenue:** Measures the overall revenue generated through sales transactions.
- **Total Profit:** Tracks the overall profit generated across sales transactions.
- **Total Units Sold:** Measures the total quantity of products sold.
- **Average Order Value (AOV):** Evaluates the average revenue generated per order.

### Regional & Product Category Performance Highlights:

- **Revenue Drivers:** Identifies top-performing product categories that contribute to the majority of overall profits, supporting more informed inventory allocation decisions.
- **Regional Opportunities:** Highlights high-performing and underperforming geographical regions, providing opportunities for targeted marketing campaigns.
- **Category Performance:** Evaluates sales distribution across different product categories using interactive bar and donut charts.
- **Sales Representative Analysis:** Enables sales performance evaluation across different sales representatives through Pivot Table aggregations.

### Monthly Sales Trends & Seasonality:

- **Monthly Revenue Trends:** Visualizes revenue fluctuations across different months through interactive line chart analysis.
- **Seasonality Analysis:** Identifies peak sales months to support proactive staffing and stock planning.
- **Time-Based Analysis:** Allows users to explore monthly sales performance through interactive year and region slicers.

---

## 🖥️ Dashboard Features & User Experience
- **Executive KPI Cards:** A centralized reporting panel displaying Total Revenue, Total Profit, Total Units Sold, and Average Order Value (AOV).
- **Regional & Category Performance:** Interactive bar and donut charts visualizing sales distribution across geographical regions and product categories.
- **Monthly Sales Trend Analysis:** A dedicated line chart illustrating revenue trends over time.
- **Interactive Slicers:** Connected slicers allow users to filter multiple Pivot Tables and charts simultaneously through a single selection.
- **Global Interactivity:** Synchronized slicer connections enable dynamic exploration of sales performance across different reporting dimensions.
- **Dynamic Visualizations:** Combines custom bar charts, line graphs, donut charts, and KPI summary cards to present sales information through an interactive reporting interface.

---

## 🛠️ Tools & Techniques Used
- **Microsoft Excel:** Core platform for data modeling, cleaning, analysis, and dashboard development.
- **Advanced Formulas:** `XLOOKUP`, `VLOOKUP`, `SUMIFS`, `AVERAGEIFS`, `COUNTIFS`, `IF`, `IFS`, and `CONCATENATE` for data retrieval, conditional calculations, and logical operations.
- **Data Cleaning & Preparation:** Duplicate removal, missing value handling, date standardization, and structured data organization.
- **Data Modeling:** Structured transactional datasets and intermediate calculation tables for analytical reporting.
- **Pivot Tables & Pivot Charts:** Dynamic aggregation and analysis of sales figures by region, category, time period, and sales representative.
- **Business Intelligence Design:** Interactive Slicers, dynamic KPI summary cards, custom bar charts, line graphs, and donut charts for executive sales reporting.

---

## ⚙️ How to Use
1. Download the `Excel_Regional_Sales_Dashboard.xlsx` file from this repository.
2. Open the workbook in **Microsoft Excel 2016 or newer** for compatibility with modern formulas and interactive slicers.
3. Navigate to the **Dashboard** worksheet to access the interactive reporting interface.
4. Use the interactive year and region slicers to filter and explore sales performance.
5. Analyze the KPI cards, regional and category visualizations, and monthly sales trends to explore the underlying sales data.
