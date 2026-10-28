# Retail Sales Analysis — Data Audit Report

## 1. Project Overview
Project Name: Retail Sales Analysis
Purpose: Analyze retail sales, profit, discounts, products, and regional performance.
Audit Status: Initial visual inspection completed; further checks pending.

## 2. Dataset Information
Dataset Filename: retail-sales-analysis
Dataset Source: kaggle
Total Records: 9,994 
Total Columns:  A to U or 21 fields

## 3. Date Range
Earliest Order Date: 02-01-2014
Latest Order Date: 11-12-2017
Date Format: The visible dates appear in day-month-year format;

## 4. Important Columns
Order ID: Visible
Order Date: Visible
Ship Date: Visible
Ship Mode: Visible
Customer ID: Visible
Customer Name: Visible
Segment: Visible
Country: Visible
City: Visible
State: Visible
Postal Code: Visible
Region: Visible
Product ID: Visible
Category: Visible
Sub-Category: Visible
Product Name: Visible
Sales: Visible
Quantity: Visible
Discount: Visible
Profit: Visible

## 5. Data Quality Checks
Missing Values: Not yet systematically checked.
Potential Duplicates: Repeated Order IDs are visible; these may represent multiple products in one order. Exact duplicate records are not yet checked.
Negative Profit: Negative profit values are visible, including approximately -172.12, -3.53, -34.95, and -43.03. These may be genuine losses and need investigation.
Discount Values: Visible values range from 0 to 0.7. Further validation is needed.
Date Formatting: Order Date and Ship Date are visible; date validity and consistency need checking.
Column Count: Pending verification.

## 6. Initial Observations
1. The dataset includes order, customer, shipping, product, sales, and profit information.
2. Sales and Profit can be used to analyze revenue and profitability.
3. Category, Sub-Category, and Product Name can support product performance analysis.
4. Region, State, and City can support geographic sales analysis.
5. Order Date, Ship Date, and Ship Mode can support shipping analysis after date validation.
6. Discount and Profit can be compared to investigate discounting and profitability.
7. Negative profit values are visible and should be investigated rather than automatically removed.

## 7. Planned Next Steps
1. Verify the number of records and columns.
2. Check missing values in each column.
3. Investigate exact duplicate records.
4. Validate dates and numeric values.
5. Investigate negative profit and discount patterns.
6. Clean the dataset only after confirming the issues.
7. Begin exploratory data analysis.

## 8. Conclusion
The initial visual inspection indicates that the dataset contains useful fields for retail sales and profitability analysis. A systematic data quality check is required before cleaning and analysis.
