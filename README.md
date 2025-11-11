# 🍕 Pizza Sales SQL Project

## 📖 Overview
This project analyzes **Pizza Sales Data** using **Structured Query Language (SQL)** to uncover insights about customer orders, sales performance, and revenue trends.  
It demonstrates SQL proficiency across both **basic** and **intermediate-level queries** including aggregation, joins, grouping, subqueries, and window functions.

---

## 🎯 Objectives
- Retrieve key performance metrics like total orders and total revenue.  
- Identify best-selling pizzas and most preferred pizza sizes.  
- Analyze sales trends by time and category.  
- Understand revenue contribution by each pizza category.  
- Use window functions for ranking and cumulative analysis.

---

## 🗂️ Database Structure

| Table | Description |
|--------|-------------|
| **orders** | Stores order ID, order date, and order time. |
| **order_details** | Contains each order item with quantity and pizza ID. |
| **pizzas** | Includes pizza ID, size, price, and type ID. |
| **pizza_types** | Includes pizza type name, category, and description. |

---

## 🧩 Basic SQL Queries

### 1️⃣ Retrieve the total number of orders placed
```sql
SELECT COUNT(order_id) AS total_orders FROM orders;
