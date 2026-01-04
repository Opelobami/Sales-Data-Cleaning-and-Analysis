# Sales-Data-Cleaning-and-Analysis (SQL Server)
This repository showcases an end-to-end SQL data analytics workflow using SQL Server, focused on transforming raw, messy sales data into analytics-ready datasets and deriving business insights.

## Project Overview
This project demonstrates a full end-to-end SQL workflow:
- Importing raw, dirty sales data
- Cleaning and validating data
- Removing duplicates safely
- Answering business questions using SQL aggregations and date functions

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

🔗 **[View messy, cleaned dataset, SQL scripts and few screenshots here---->](https://drive.google.com/drive/folders/1lisCIi2rWess14IepEHl3K-mNe_ZYyUl?usp=drive_link)**  

---

## Data Cleaning Steps
1. Removed duplicate order IDs using a surrogate key
2. Standardized categorical fields (region, country and product_category)
3. Cleaned and validated numerical fields (quantity, unit price, and discount)
4. Recalculated sales amount from clean inputs
5. Standardized returned flag to 1 (Returned), 0 (Not Returned) and NULL for empty returned.
6. Created clean, reusable tables for analysis

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

## Tools and SKills demonstrated
- SQL Server (T-SQL)
- Google docs
- data cleaning and validation
- Business-driver analytics
- Reproducible SQL workflows
- GitHub documentation best practices

---

## Why this Project Matters
This project demonstrates the ability to work with imperfect real-world data, apply sound data quality principles, and translate raw data into meaningful business insights using SQL. It reflects the type of analytical work performed in production environments by data analysts and analytics engineers

## Key Learnings
- Practical data cleaning in SQL
- Handling real-world messy data
- Writing business-focused SQL queries
- Structuring an analytics portfolio project
