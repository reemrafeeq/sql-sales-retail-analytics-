# 📊 Sales Analytics Using PostgreSQL

## 📌 Project Overview

This project focuses on analyzing sales data using PostgreSQL to identify business trends, understand customer purchasing behavior, and evaluate product performance.

The goal is to transform raw sales data into meaningful business insights that help organizations make better data-driven decisions.

## 🗄️ Database Structure

The project uses a simple Star Schema consisting of three tables:

### 1. dim_customer
Stores customer information.

- customer_id
- customer_name
- city

### 2. dim_product
Stores product information.

- product_id
- product_name
- category
- price

### 3. fact_sales
Stores sales transaction details.

- sale_id
- customer_id
- product_id
- quantity
- sale_date

## 🛠️ Tools & Technologies

- PostgreSQL
- SQL
- pgAdmin / psql
- Git & GitHub

## 📚 SQL Concepts Used

- SELECT and WHERE
- INNER JOIN and LEFT JOIN
- GROUP BY and HAVING
- Aggregate Functions (SUM, COUNT, AVG)
- Common Table Expressions (CTEs)
- Subqueries
- CASE statements
- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- Window Functions
- Running Totals
- EXTRACT() for date analysis
- Materialized Views

## 📈 Business Analysis

The project answers important business questions:

1. What is the total revenue generated?
2. Which products generate the highest revenue?
3. Which customers spend the most?
4. Which city generates the highest revenue?
5. Which product category contributes the most revenue?
6. What are the monthly revenue trends?
7. Who are the top three customers by spending?
8. Which products sell the highest quantity in each category?
9. Which customers make repeat purchases?
10. What is the daily revenue trend?
11. What percentage of revenue comes from each category?
12. What is the average spending per customer purchase?
13. Which products have never been sold?
14. Which are the top two products by revenue?
15. Who are the highest-spending customers in each city?

## 💡 Key Business Insights

- Identified high-revenue products to understand product performance.
- Analyzed customer spending to identify valuable customers.
- Compared revenue across different cities.
- Evaluated category-wise revenue contribution.
- Analyzed monthly and daily revenue trends.
- Identified repeat customers and purchasing patterns.
- Found best-selling products in each category.
- Calculated average spending per purchase.

## ⚡ Database Optimization

Created a Materialized View named `mv_product_sales` to store precomputed product sales information.

This helps retrieve product-level sales summaries without repeatedly performing the same aggregation query.

## 📁 Project Structure

```text
Sales-Analytics/
│
├── SQL/
│   └── sales_analysis.sql
│
├── Reports/
│   └── business_insights.md
│
├── Dashboard/
│   └── sales_dashboard.pbix
│
└── README.md
```

## 🎯 Project Outcome

Through this project, I gained practical experience in PostgreSQL and learned how to use SQL for business analysis.

I practiced joining multiple tables, analyzing sales performance, ranking customers and products, calculating revenue, and identifying useful business insights.

## 👩‍💻 Author

**Reem Rafeeq**

Aspiring Data Analyst | PostgreSQL | SQL | Data Analytics
