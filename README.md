# Vehicle Sales Analytics Project

## Overview

This project analyzes over **548,000 vehicle sales transactions** to uncover market trends, pricing patterns, inventory distribution, and profitability performance.

The solution combines **SQL**, **Python**, and **Tableau** to build an end-to-end analytics workflow - from raw data processing to executive-level dashboard reporting.

---

## Business Problem

Used vehicle markets generate massive transaction volumes, making it difficult to monitor:

* Sales performance
* Revenue generation
* Pricing trends
* Inventory composition
* Profitability against market estimates

This project transforms raw auction sales data into actionable business insights through automated data preparation and interactive visual analytics.

---

## Tech Stack

| Tool                                        | Purpose                                    |
| ------------------------------------------- | ------------------------------------------ |
| SQL (DBeaver)                               | Data cleaning and transformation           |
| Python (Pandas, NumPy, Matplotlib, Seaborn) | Data preprocessing and feature engineering |
| Tableau Public                              | Interactive dashboard development          |

---

## Project Workflow

### 1. SQL Data Preparation

Performed data standardization and business-rule transformations:

* Standardized vehicle body categories
* Cleaned transmission values
* Created condition classifications
* Normalized state codes
* Generated derived business fields

### 2. Python Data Engineering

Built a scalable preprocessing pipeline to:

* Clean 500K+ vehicle sales records
* Handle missing and invalid values
* Engineer business KPIs
* Create analytical datasets for reporting

Key engineered metrics:

* Profit/Loss vs Market Value (MMR)
* Vehicle Age
* Condition Grade
* Transmission Category
* Monthly Sales Trends

### 3. Business Analysis

Conducted exploratory and strategic analysis including:

* Market inventory concentration
* Price distribution analysis
* Asset depreciation trends
* Regional profitability comparison
* Sales velocity monitoring
* Revenue contribution by vehicle segment

### 4. Tableau Dashboard

Developed an executive dashboard to monitor:

* Total Vehicles Sold
* Total Revenue
* Average Sale Price
* Average Profit/Loss
* Top Brands by Volume
* Monthly Sales Trends
* Vehicle Body Composition
* Transmission Distribution

---

## Dashboard Preview

[![Vehicle Sales Dashboard](Vehicle%20Sales%20Executive%20Dashboard.png)](https://public.tableau.com/views/Book1_17815063637320/VehicleSalesExecutiveDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### Interactive Tableau Dashboard

👉 [Paste your Tableau Public link here](https://public.tableau.com/views/Book1_17815063637320/VehicleSalesExecutiveDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Key Results

| KPI                 |        Value |
| ------------------- | -----------: |
| Total Vehicles      |      548,367 |
| Total Revenue       | $7.5 Billion |
| Average Sale Price  |      $13,690 |
| Average Profit/Loss |        -$159 |

---

## Repository Structure

```text
Vehicle-sales-project
│
├── AutoSales.sql
├── vehicle_sales_prj.py
├── Vehicle Sales Executive Dashboard.png
├── README.md
│
└── data
    ├── car_prices.csv
    ├── vehicle_sales_final.csv
    └── Clean_Auto_Sales.xlsx
```

---

## Skills Demonstrated

* SQL Data Transformation
* Data Cleaning
* ETL Development
* Feature Engineering
* Exploratory Data Analysis (EDA)
* KPI Design
* Business Analytics
* Tableau Dashboard Development
* Data Storytelling

---

## Author

Minh Ngoc Le
