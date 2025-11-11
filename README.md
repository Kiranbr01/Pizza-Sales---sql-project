# 🍕 Pizza Sales SQL Project

## 📖 Overview
An analytical SQL project exploring **pizza sales data** to uncover insights on revenue, order patterns, and product performance.  
It demonstrates SQL skills through aggregation, joins, grouping, and window functions.

---

## 🎯 Objectives
- Calculate key business metrics like total sales and orders.  
- Identify best-selling pizzas and categories.  
- Analyze order trends by time and size.  
- Evaluate category-wise revenue contributions.

---

## 🗂️ Database Tables
| Table | Description |
|--------|-------------|
| **orders** | Order IDs, dates, and times |
| **order_details** | Order-level pizza quantities |
| **pizzas** | Pizza size, price, and type ID |
| **pizza_types** | Pizza names and categories |

---

## 🧩 SQL Highlights
- Aggregations using `SUM`, `COUNT`, `AVG`  
- Multi-table joins for combined insights  
- Time-based grouping with `HOUR()` and `DATE()`  
- Window functions (`RANK()`, `OVER()`) for ranking and cumulative totals  
- Subqueries for daily and category averages  

---

## 📊 Key Insights
- **Large pizzas** were most frequently ordered.  
- **Classic and Supreme** categories led total sales.  
- Top 3 pizzas generated most of the revenue.  
- Peak orders occurred during **evening hours**.  
- Cumulative revenue showed consistent growth

---

## 🚀 How to Use
1. Clone the repo  
   ```bash
   git clone https://github.com/<your-username>/pizza-sales-sql-project.git

