# Retail Profitability Analysis Project

## Overview

This project analyzes retail sales, revenue, costs, and profitability to identify trends, high-performing products, customer purchasing behavior, and opportunities to improve business performance.

Using SQL, I transformed and analyzed transactional sales data to answer key business questions related to revenue generation, profit margins, product performance, customer behavior, and regional trends.

---

## Business Objective

The goal of this project is to help business stakeholders understand:

* Which products and categories generate the most revenue
* Which products generate the highest profit
* Seasonal sales patterns
* Regional performance differences
* Customer purchasing behavior
* Opportunities to improve profitability

---

## Dataset

The project utilizes three primary datasets:

### Orders

Contains transaction-level sales information.

Key fields:

* Order ID
* Customer ID
* Product ID
* Order Date
* Quantity
* Revenue
* Cost of Goods Sold (COGS)

### Customers

Contains customer demographic information.

Key fields:

* Customer ID
* Customer Join Date
* Region

### Products

Contains product information.

Key fields:

* Product ID
* Product Name
* Product Category
* Product Price
* Base Cost

---

## Data Preparation

Several data-cleaning and transformation steps were performed:

### Date Conversion

Order dates existed in multiple formats:

* MM/DD/YYYY
* YYYY-MM-DD

Dates were standardized using MySQL's `STR_TO_DATE()` function.

### Profit Calculation

Profit was calculated using:

```sql
Revenue - COGS
```

### Week Start Calculation

Weekly analysis was performed by deriving the beginning of each week from transaction dates.

---

## Business Questions Answered

### Revenue Analysis

* What is total revenue?
* What are monthly revenue trends?
* Which seasons generate the most sales?
* Which product categories generate the most revenue?

### Profitability Analysis

* What is total profit?
* Which products generate the highest profit?
* Which categories have the highest profit margins?
* Which categories are underperforming?

### Product Performance

* Top-selling products by quantity
* Top-selling products by revenue
* Most profitable products
* Lowest-performing products

### Customer Analysis

* Revenue by customer
* Average customer value
* Customer acquisition trends
* Repeat purchasing behavior

### Regional Analysis

* Revenue by region
* Profit by region
* Regional sales trends

---

## Skills Demonstrated

### SQL

* Joins
* Aggregations
* CASE Statements
* Date Functions
* Window Functions
* Subqueries
* Common Table Expressions (CTEs)
* Profit Calculations

### Data Analysis

* Trend Analysis
* Revenue Analysis
* Profitability Analysis
* Business KPI Development
* Customer Segmentation

### Business Intelligence

* KPI Reporting
* Executive-Level Insights
* Strategic Recommendations

---

## Key Findings

### Seasonal Performance

* Spring generated the highest revenue.
* Autumn generated the lowest revenue.

### Product Categories

* Electronics consistently produced strong sales.
* Footwear performed exceptionally well during Spring.
* Winter sports products peaked during Winter months.

### Customer Insights

* Certain customer segments contributed significantly more revenue than others.
* Repeat customers represented a substantial portion of total sales.

### Profitability

* Several products generated strong revenue but lower profit margins.
* Identifying high-margin products provides opportunities for targeted marketing and promotion.

---

## Tools Used

* MySQL
* Power BI
* Excel
* GitHub

---

## Project Deliverables

* SQL Queries
* Data Cleaning Scripts
* Business Analysis
* KPI Development
* Visual Dashboard
* Executive Summary

---

## Author

Josh Smith

Aspiring Data Analyst focused on transforming raw data into actionable business insights through SQL, Power BI, and data storytelling.
