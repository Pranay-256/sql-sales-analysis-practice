# 🛒 SQL Sales Analysis Practice

This repository contains my SQL practice queries based on a sales dataset. The exercises cover fundamental to intermediate SQL concepts including filtering, sorting, aggregation, grouping, subqueries, CASE statements, and joins.

The objective of this project was to strengthen my SQL query-writing skills by solving common business-related problems that are frequently asked in interviews and SQL assessments.

---

## 📌 Dataset Overview

The dataset contains sales transaction information with the following fields:

| Column          | Description             |
| --------------- | ----------------------- |
| `order_id`      | Unique order identifier |
| `customer_name` | Customer name           |
| `order_date`    | Date of purchase        |
| `category`      | Product category        |
| `sub_category`  | Product sub-category    |
| `product_name`  | Product name            |
| `quantity`      | Quantity purchased      |
| `unit_price`    | Price per unit          |
| `total_price`   | Total order value       |
| `region`        | Sales region            |

---

# 🛠 SQL Concepts Covered

* SELECT Statement
* WHERE Clause
* ORDER BY
* GROUP BY
* Aggregate Functions

  * SUM()
  * AVG()
  * COUNT()
  * MAX()
* HAVING Clause
* LIMIT
* BETWEEN
* CASE Statements
* Subqueries
* INNER JOIN
* Table Creation (DDL)

---

# 📚 Queries Included

### Basic Queries

* Display all records
* Select specific columns
* Filter data using `WHERE`
* Sort records using `ORDER BY`
* Filter records using `BETWEEN`
* Display Top N records

---

### Aggregate Functions

* Total Revenue
* Average Order Value
* Total Number of Orders
* Revenue by Category
* Average Unit Price by Category
* Orders by Region
* Quantity Sold by Region

---

### Business Analysis Queries

* Highest Revenue Category
* Top 5 Customers by Sales
* Most Expensive Product
* Customers Spending Above Average
* Top 10 Highest Value Orders

---

### CASE Statement

Categorized every order into:

* 🟢 High Value
* 🟡 Medium Value
* 🔴 Low Value

based on the total order value.

---

### Subqueries

Used subqueries to compare customer spending against the overall average order value.

---

### Joins

Performed an **INNER JOIN** between two sales tables to retrieve:

* Customer Name
* Product Name
* Category
* Total Price

---

## 📂 Repository Structure

```text
sql-sales-analysis-practice/
│
├── datasets/
│   ├── SQL_Sales_Dataset.csv
│   └── SQL_Sales_Dataset2.csv
│
├── sql file/
│   └── sql sales analysis practice.sql
│
└── README.md
```

---

# 💻 Technologies Used

* SQL
* PostgreSQL (queries written using PostgreSQL syntax)

---

# 🎯 Skills Demonstrated

* Data Retrieval
* Data Filtering
* Sorting
* Aggregations
* Business Analysis using SQL
* Data Grouping
* Conditional Logic
* Joins
* Subqueries
* SQL Query Optimization Basics

---

# 📈 Sample Business Questions Solved

* What is the total revenue generated?
* Which category generated the highest sales?
* Who are the top customers?
* Which product is the most expensive?
* Which customers spent more than the average?
* How many orders were placed in each region?
* What is the average order value?
* Which orders are High, Medium, and Low value?

---

# 🚀 Learning Outcome

This project helped reinforce essential SQL concepts commonly tested in technical interviews and data analyst assessments. It provided hands-on experience in writing efficient SQL queries to extract insights from transactional sales data while improving problem-solving and analytical thinking.

---

## ⭐ If you found this project useful, consider giving the repository a star!
