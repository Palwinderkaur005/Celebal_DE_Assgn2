# Celebal_DE_Assgn2
# 📊 SQL Sales Analysis & E-Commerce Database Assignment

## 📌 Project Overview

This project demonstrates SQL concepts through two datasets:

1. **Superstore Sales Dataset** – Sales analysis using filtering, aggregation, sorting, grouping, and business insights.
2. **ShopEase E-Commerce Database** – Relational database analysis involving customers, products, orders, and order items using SQL queries, joins, constraints, indexes, and transactions.

The objective is to apply SQL for data exploration, business reporting, and database management while gaining hands-on experience with real-world datasets.

---

## 🎯 Objectives

* Create and manage relational databases.
* Perform data retrieval using SELECT statements.
* Apply filtering using WHERE conditions.
* Use aggregate functions such as SUM, COUNT, AVG, MIN, and MAX.
* Analyze customer behavior and sales performance.
* Implement JOIN operations across multiple tables.
* Understand Primary Keys, Foreign Keys, Constraints, and Indexes.
* Perform transaction management using COMMIT and ROLLBACK.
* Generate meaningful business insights from data.

---

# Part A: Superstore Sales Analysis

## Dataset

* Superstore Sales Dataset
* Source: Kaggle

## Tasks Performed

### Data Exploration

* Viewed table structure.
* Examined sample records.
* Verified row counts.

### Filtering Operations

* Region-wise filtering.
* Category-wise filtering.
* Date-based filtering.
* Sales threshold analysis.

### Aggregation

* Total Sales by Region.
* Sales by Category.
* Profit Analysis.
* Quantity Sold Analysis.

### Sorting & Ranking

* Top Products by Sales.
* Top Customers by Revenue.
* Top Categories by Performance.

### Business Use Cases

* Monthly Sales Trends.
* Revenue Analysis.
* Customer Purchase Analysis.
* Duplicate Record Detection.

### Data Validation

* Row Count Verification.
* Missing Value Checks.
* Duplicate Detection.
* Data Quality Assessment.

---

## Key Insights

* Technology products generated significant revenue.
* Sales performance varied across regions.
* Top customers contributed a large portion of total revenue.
* Certain products generated higher profits than others.
* Monthly sales trends revealed peak purchasing periods.

---

# Part B: ShopEase E-Commerce Database

## Database Schema

### Customers

Stores customer details including:

* Customer ID
* Name
* Email
* Location
* Membership Status

### Products

Stores product information including:

* Product Name
* Category
* Brand
* Unit Price
* Stock Quantity

### Orders

Stores customer orders including:

* Order Date
* Status
* Total Amount

### Order Items

Stores product-level order details including:

* Quantity
* Price
* Discount

---

## Entity Relationships

customers (1:N) orders

orders (1:N) order_items

products (1:N) order_items

---

## SQL Concepts Covered

### SQL Basics

* SELECT
* DISTINCT
* Constraints
* Primary Keys
* Unique Keys

### Filtering & Optimization

* WHERE Clause
* Date Filtering
* Index Usage
* Query Optimization

### Aggregation

* COUNT()
* SUM()
* AVG()
* MIN()
* MAX()
* GROUP BY
* HAVING

### Joins

* INNER JOIN
* LEFT JOIN
* Relationship Analysis

### Advanced SQL

* CASE Statements
* ACID Properties
* Transactions
* COMMIT
* ROLLBACK

---

## Business Questions Solved

### Customer Analysis

* Customer information retrieval.
* Premium customer identification.
* Customer location analysis.

### Product Analysis

* Category-wise products.
* Price analysis.
* Inventory monitoring.

### Order Analysis

* Delivered orders.
* Pending orders.
* Cancelled orders.
* Revenue tracking.

### Sales Performance

* Revenue by order status.
* Average product prices.
* Category profitability.

### Relationship Analysis

* Customer orders.
* Product sales.
* Order item details.

---

## Tools & Technologies

* MySQL Workbench
* SQL
* Relational Database Management System (RDBMS)

---

## Files Included

Celebal_DE_Assgn2/
│
├── README.md
├── Superstore_analysis.sql
├── ShopEase_Database.sql
├── DE_Assgn2 ques-ans.pdf
├── SQL_Queries&Result.pdf
├── archive(2).zip
├── Screenshots/
│   ├── SQL_Queries& Result SS
│   ├── DE_Assgn2 ques-ans SS
│   

```


## Learning Outcomes

Through this project, I gained practical experience in:

* Writing efficient SQL queries.
* Working with relational databases.
* Performing data analysis using SQL.
* Understanding database constraints and indexing.
* Applying joins and aggregation techniques.
* Implementing transaction management.
* Generating business insights from structured data.

---

## Conclusion

This project demonstrates the practical use of SQL for business analytics and database management. By analyzing sales data and managing an e-commerce database, valuable insights were generated regarding customer behavior, product performance, revenue trends, and operational efficiency.
