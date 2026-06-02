# E-commerce Customer & Revenue Analysis (SQL)

## Problem
Analyze e-commerce data to understand customer behavior, revenue contribution, and retention patterns in order to support business decision-making.

---

## Dataset
Relational dataset containing the following tables:
- customers
- orders
- products
- order_items
- payments

---

## Approach
- Joined multiple tables to create a unified analytical dataset
- Used aggregations to compute KPIs such as revenue and average order value
- Applied CASE statements for customer segmentation
- Used window functions (RANK, ROW_NUMBER, LAG) for ranking, sequencing, and behavioral analysis
- Performed time-based analysis using date functions
- Calculated revenue contribution and customer lifetime metrics

---

## Key Insights
- A small percentage of customers contribute a large share of total revenue
- Repeat customers show shorter purchase intervals than inactive users
- Customer lifetime varies significantly, indicating multiple behavioral segments
- Revenue trends show consistent growth over time
- High-value repeat customers are the most critical segment for retention strategies

---

## Tech Stack
- SQL (MySQL)
- MySQL Workbench
- GitHub

---

## How to Run
1. Create a database in MySQL
2. Execute `schema.sql` to create tables
3. Import CSV files into corresponding tables
4. Run queries from `ecommerce_business_analysis.sql`

---

## Project Structure

ecommerce-sql-analysis/
│
├── schema.sql
├── ecommerce_business_analysis.sql
└── data/
    ├── ecommerce_customers.csv
    ├── ecommerce_orders.csv
    ├── ecommerce_products.csv
    ├── ecommerce_order_items.csv
    └── ecommerce_payments.csv

---

## Summary
This project demonstrates the use of SQL to extract, transform, and analyze structured data to generate business insights and support decision-making.

---

## Author
Aditya  
Aspiring Data Analyst
linkdin:-https://www.linkedin.com/in/aditya-h-unnad
