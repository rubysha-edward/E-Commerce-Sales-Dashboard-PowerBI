# E-Commerce Sales Dashboard Using Microsoft Power BI

![Power BI](https://img.shields.io/badge/Microsoft%20Power%20BI-Dashboard-F2C811?logo=powerbi\&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-green)
![Project](https://img.shields.io/badge/Project-E--Commerce%20Analytics-purple)

## Project Overview

The **E-Commerce Sales Dashboard** is an interactive Business Intelligence project developed using Microsoft Power BI to analyze e-commerce sales transactions and generate meaningful business insights.

The project uses an e-commerce sales dataset containing approximately **34,500 records** related to customers, products, orders, revenue, profitability, and geographic regions.

Power Query was used for data cleaning and transformation, while DAX was used to develop analytical measures and key performance indicators (KPIs). The final dashboard provides an interactive view of sales performance, customer behaviour, product performance, and transaction-level details.

## Project Objectives

* Analyze overall e-commerce sales and profitability.
* Clean and transform transactional data using Power Query.
* Develop a structured data model using fact and dimension tables.
* Create DAX measures and KPIs for business performance monitoring.
* Analyze customer demographics and purchasing behaviour.
* Compare product category and regional performance.
* Enable interactive exploration through slicers and drillthrough functionality.

## Dashboard Pages

### 1. Executive Sales Overview

Provides a high-level view of business performance through revenue, profit, total orders, average order value, sales trends, category contributions, and regional performance.

### 2. Customer Analysis

Examines customer demographics, customer activity, gender-based revenue distribution, customer purchasing behaviour, and return-related metrics.

### 3. Product Performance Analysis

Evaluates product categories, pricing, quantity sold, revenue contribution, and profitability using interactive visualizations.

### 4. Transactional Drillthrough Details

Enables users to explore detailed sales transaction records and move from summarized results to individual order-level information.

## Key Performance Indicators (KPIs)

The dashboard includes measures such as:

* Total Revenue
* Total Profit
* Total Orders
* Total Customers
* Total Quantity Sold
* Average Order Value (AOV)
* Profit Margin %
* Returned Orders
* Return Rate %
* Purchase Frequency
* Average Delivery Days
* Revenue Month-over-Month (MoM) %
* Revenue Year-over-Year (YoY) %

## Tools and Technologies

* **Microsoft Power BI Desktop** — Dashboard development and visualization
* **Power Query** — Data cleaning, transformation, and preparation
* **DAX (Data Analysis Expressions)** — Measures, calculated columns, and KPIs
* **Data Modelling** — Relationships between fact and dimension tables
* **GitHub** — Project documentation and version control

## Data Model

The project uses a structured model consisting of a central sales fact table and supporting dimension tables.

* `Fact_Sales` — Transactional sales data
* `Dim_Customer` — Customer attributes and age groups
* `Dim_Product` — Product and category information
* `Dim_Location` — Geographic attributes
* `Dim_Calendar` — Date-based analysis and time intelligence

This model supports filtering and analysis across customers, products, locations, and time periods.

## Data Preparation and Analysis

The project workflow includes:

1. Importing the e-commerce dataset into Power BI.
2. Inspecting and transforming data in Power Query.
3. Validating data types, identifiers, and data consistency.
4. Creating relationships between fact and dimension tables.
5. Developing DAX measures for business KPIs.
6. Building interactive charts, KPI cards, and analytical visuals.
7. Implementing slicers and transaction-level drillthrough.

## Repository Contents

The repository will contain the Power BI project file, dashboard screenshots, and project documentation as these files are added.

```text
E-Commerce-Sales-Dashboard-PowerBI/
│
├── README.md
├── E-Commerce-Sales-Dashboard.pbix
├── dataset/
│   └── e_commerce_sales_data.csv
├── screenshots/
│   ├── executive-sales-overview.png
│   ├── customer-analysis.png
│   ├── product-performance.png
│   └── transaction-drillthrough.png
└── report/
    └── E-Commerce-Sales-Dashboard-Report.pdf
```

*Note: The structure above is the intended organization. Add only the files and folders that actually exist in the repository, and update the filenames to match your uploaded files.*

## Business Value

The dashboard demonstrates how raw e-commerce transaction data can be transformed into an interactive reporting solution that helps users:

* Monitor revenue and profitability.
* Identify high-performing product categories and regions.
* Understand customer behaviour.
* Track order returns and delivery performance.
* Explore business performance at summary and transaction levels.

## Future Enhancements

* Connect the dashboard to a live SQL database.
* Automate data refresh.
* Explore sales forecasting and customer segmentation.
* Extend the analysis with additional business intelligence metrics.

## Author

**Rubysha E**
B.Sc. Data Science
PSGR Krishnammal College for Women, Coimbatore, Tamil Nadu, India

## Project Context

Developed as an internship project focused on Business Intelligence and e-commerce analytics using Microsoft Power BI.
