# Ferns-and-Petals-Sales-Analysis

## 📌 Project Overview

To analyze Ferns & Petals’ order, customer, and product data to uncover trends in sales performance, customer behavior, delivery timelines, and purchasing patterns—enabling data-driven decisions to improve revenue and customer satisfaction.

## 📂 Dataset Description

- Customers Table (7 columns)
- Orders Table (18 columns)
- Products Table (5 columns)

## 📂 Data Model

1. Orders linked to Customers using CustomerID
2. Orders linked to Products using ProductID
3. Star-schema model ensuring efficient aggregations

## 📊 Approach

1. Data Extraction & Cleaning using Excel and Power Query
- Removed duplicates, fixed inconsistent formats, validated dates & categories.

2. Data Modeling in Power Pivot
- Built relationships between Customers, Orders, and Products tables.
- Created calculated columns (Order Month, Order Hour, Days to Deliver, Revenue).

3. KPI Development using Power Pivot measures.

4.Interactive Dashboards built with pivot tables, pivot charts, and slicers.

## 📊 KPIs Used

Dashboard 1: Sales & Product Performance
- Total Orders: 100
- Total Revenue: ₹35,20,984
- Total Quantity Sold: 3045
- Average Days to Deliver: 5.53 days

Dashboard 2: Customer & Order Insights
- Total Customers: 100
- Average Delivery Hour: 11 hrs 16 mins
- Average Customer Spending: ₹3,520.98
- Multiple Orders by Customers: 804


📊 Dashboards Overview
Page 1 — Sales & Product Performance

1. Monthly Revenue (Line Chart) – August highest (₹7.37L)

2. Revenue by Category (Column Chart) – Colors lead with ₹10.05L

3. Revenue by Day (Bar Chart) – Tuesday highest at ₹6.77L

4. Top 5 Products by Revenue (Donut Chart) – Magnam Set (22%)

5. Revenue by Occasion (Bar Chart) – Anniversary highest at ₹6.74L

6. Revenue & Quantity by City (Column + Area Chart)
- Slicers: Gender, Occasion, Order Date Timeline

Page 2 — Customer & Order Insights

1. Orders by Gender (Donut) – Female > Male

2. Top 5 Cities by Orders (Bar) – Imphal (29)

3. Occasion by Gender (Stacked Column) – Anniversary, majorly by males (53,308 value)

4. Delivery Time Distribution (Line) – ~60 orders delivered in 8 days

5. Peak Order Hour (Line) – 9th hour

6. Top 10 Frequent Buyers – Customer ID C044 purchased 17 items
- Slicers: Gender, Occasion

## 🛠 Tools Used
- Microsoft Excel
- Power Query
- Power Pivot

## 📘 Project Learnings
- Performed data cleaning & transformation using Power Query
- Built a star-schema data model in Power Pivot
- Created calculated columns & measures for KPIs
- Designed interactive dashboards with multi-level filtering
- Interpreted insights to answer real business questions

## 👩‍💻 Developed By  
**Rashmi Sharma**  
*Data Analyst | SEO Executive | Digital Marketing*  

📧 [Mail ID](mailto:rashusharma007@gmail.com)

🔗 [LinkedIn Profile](https://www.linkedin.com/in/rashmi-sharma-11nv91)
