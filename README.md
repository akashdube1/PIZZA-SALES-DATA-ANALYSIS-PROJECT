# PIZZA-SALES-DATA-ANALYSIS-PROJECT
This project is a comprehensive SQL-based analysis of a pizza sales dataset. It showcases my ability to write basic, intermediate, and advanced SQL queries to extract business insights from real-world data.

# 🍕 Pizza Sales SQL Project

This project is a comprehensive analysis of a fictional pizza sales dataset using SQL. It showcases practical skills in writing queries for real-world business use cases like revenue analysis, product performance, and customer behavior insights.

---

## 📁 Dataset Overview

This project uses a pizza sales dataset consisting of four main tables:

| Table Name       | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| `orders`         | Contains order IDs and the corresponding order date and time.               |
| `order_details`  | Contains individual items per order including pizza type and quantity.      |
| `pizzas`         | Contains information about each pizza including size and price.             |
| `pizza_types`    | Describes each pizza type, its name, category (e.g., classic, veggie), and ingredients. |

### 🔗 Table Relationships:
- Each `order` can have multiple `order_details`.
- Each `order_detail` references a `pizza_id` from the `pizzas` table.
- Each `pizza` links to a `pizza_type` that holds category and ingredient details.

---

## 🛠️ Tools Used

- SQL (PostgreSQL / MySQL)
- Excel / CSV (for the dataset)

---

## 🎯 Project Objectives

- Practice SQL skills through real-world problem-solving  
- Analyze sales data to find patterns and trends  
- Break down queries into Basic, Intermediate, and Advanced levels for structured learning

---

## ✅ Basic SQL Queries

1. Retrieve the total number of orders placed  
2. Calculate the total revenue generated from pizza sales  
3. Identify the highest-priced pizza  
4. Identify the most common pizza size ordered  
5. List the top 5 most ordered pizza types along with their quantities  

---

## 🔄 Intermediate SQL Queries

6. Find the total quantity of each pizza category ordered  
7. Determine the distribution of orders by hour of the day  
8. Find the category-wise distribution of pizzas  
9. Group the orders by date and calculate the average number of pizzas ordered per day  
10. Determine the top 3 most ordered pizza types based on revenue  

---

## 🔬 Advanced SQL Queries

11. Calculate the percentage contribution of each pizza type to total revenue  
12. Analyze the cumulative revenue generated over time  
13. Determine the top 3 most ordered pizza types based on revenue for each pizza category  

---

## 📈 Sample Insights

- Medium-sized pizzas were the most ordered across all categories  
- The **BBQ Chicken** pizza had the highest total revenue  
- Peak order time was between **6 PM – 8 PM**, showing typical dinner behavior  
- **Vegetarian pizzas** performed better than expected in terms of both quantity and revenue  
- Cumulative revenue showed a healthy and consistent growth over time

---

## 🧩 Entity Relationship Diagram

The following ER diagram shows the relationship between tables in the database:

![Entity Relationship Diagram](er_diagram.png)

---

## 📌 Conclusion

This project demonstrates how SQL can be used to gain actionable insights from sales data. From identifying top-performing products to understanding customer behavior by time, size, and category, each query helps mimic a real business analyst’s workflow.

Future improvements may include:
- Creating dashboards using Power BI or Tableau  
- Automating insights using Python or stored procedures  
- Connecting this data to a live front-end dashboard

---

## 📂 Project Structure

