# Power BI Sales Dashboard

This project is a sales analysis dashboard built in Power BI.

I created the dashboard to practice turning raw sales data into a clear and interactive report that can be used to explore business performance from different perspectives.

## What the dashboard shows

The report contains three pages:

### Executive Dashboard

A quick overview of the business performance:

- Revenue
- Cost
- Profit
- Margin
- YoY Growth
- Monthly Revenue Trend
- Revenue and Profit by Product Category

### Sales Analysis

A more detailed look at sales performance:

- Total Sales
- Orders KPI
- Average Order Value
- Revenue by Territory
- Top 5 Salespersons
- Top 5 Customers
- Top 5 Products

The page can be filtered by Year and Territory.

### Product Analysis

Focuses on product performance:

- Top 5 Products by Revenue
- Top 5 Products by Profit
- Top 5 Subcategories by Revenue
- Profit Margin by Category

The page can be filtered by Year and Category.

## Data Model

The report uses a star-schema approach with a central `FactSales` table and related dimension tables for:

- Products
- ProductCategory
- ProductSubcategory
- Customers
- SalesPerson
- SalesTerritory
- Calendar

## Measures

Some of the main DAX measures used in the report include:

- Total Sales
- Total Cost
- Total Profit
- Profit Margin
- Orders
- Average Order Value
- Sales Previous Year
- YoY Growth %

## Tools

- Power BI
- DAX
- Power Query
- Excel

## What I practiced

While working on this project, I practiced:

- Building a data model
- Creating relationships between tables
- Writing DAX measures
- Creating interactive dashboards
- Using slicers and filters
- Choosing appropriate visualizations for different business questions
- Formatting and organizing a multi-page Power BI report

## Project Preview

Screenshots of the dashboard are included below.
