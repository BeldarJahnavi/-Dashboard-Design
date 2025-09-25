📊 Sales Performance Dashboard — Superstore
📌 Overview

This project is part of Task 3: Dashboard Design for a Data Analyst Internship.

The goal was to design an interactive Power BI dashboard to analyze sales, profit, categories, customers, and regional performance using the popular Kaggle Sample Superstore dataset.

📑 Dataset

Source: Kaggle – Sample Superstore

Size: ~10k rows

Key Columns:

Order Date, Ship Date

Sales, Profit, Quantity, Discount

Category, Sub-Category, Region, Customer Name
⚙️ Steps Performed

Data Loading & Cleaning (Power Query)

Changed data types (dates, numbers).

Removed duplicates & handled nulls.

Added derived columns (Year, Month, Quarter, YearMonth).

Data Modeling

Built a proper Date table using DAX.

Created relationships between tables.

DAX Measures

Total Sales, Total Profit, Profit Margin %

Orders Count, Average Order Value (AOV)

YoY Growth %, MoM %, Sales YTD

Dashboard Design

KPI Cards (Sales, Profit, Margin, AOV)

Sales vs Profit (Scatter)

Sales by Region (Map)

Sales by Category (Bar Chart)

Top 10 Customers (Table)

Filters: Region, Category, Segment, Date

📸 Dashboard Preview

(Insert screenshot from screenshots/ folder here)

📑 Key Insights

Total Sales: 2.30M

Total Profit: 286.4K

Profit Margin: 12%

AOV: 458.6

Technology is the most profitable category.

Furniture has low/negative profit margins due to heavy discounts.

Central region contributes significantly to sales.
