# Sales-Data-Cleaning-and-Analysis (SQL Server)
This repository showcases an end-to-end SQL data analytics workflow using SQL Server, focused on transforming raw, messy sales data into analytics-ready datasets and deriving business insights.

## Project Overview
This project demonstrates a full end-to-end SQL workflow:
- Importing raw, dirty sales data
- Cleaning and validating data
- Removing duplicates safely
- Performing business analysis using SQL

The goal is to simulate real-world analytical work using SQL Server.

---

## Dataset
- 50,000 rows of synthetic sales data
- Contains intentional data quality issues:
  - Duplicate order IDs
  - NULL customer IDs
  - Negative quantities and sales
  - Null and invalid discounts
  - Inconsistent return flags

---

## Data Cleaning Steps
1. Removed duplicate order IDs using a surrogate key
2. Standardized region using the CASE function
3. Cleaned quantity, unit price, and discount columns
4. Recalculated sales amount from clean inputs
5. Standardized returned flag to 1 (Returned) and 0 (Not Returned)
6. Applied CHECK constraints to enforce data quality

---

## Business Questions Answered
- What is the total sales for returned vs non-returned orders?
- Which region generates the highest revenue?
- Which product category performs best?
- What is the average order value?
- Which sales channel drives more revenue?
- Do higher discounts lead to more returns?
- What percentage of sales is from returned orders?

---

## Tools Used
- SQL Server
- T-SQL
- GitHub

---

## Key Learnings
- Practical data cleaning in SQL
- Handling real-world messy data
- Writing business-focused SQL queries
- Structuring an analytics portfolio project
