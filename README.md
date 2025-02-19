# Pizza Sales Analysis

## Project Overview
This project analyzes **Pizza Sales Data** using **SQL for data querying** and **Power BI for visualization and data cleaning**.  
It provides insights into sales trends, customer behavior, and revenue generation.

---

## Dataset Details
- **File Name:** `Pizza Sales.pbix`
- **Tool Used:** Power BI, SQL
- **Key Data Fields:**
  - `order_id` – Unique identifier for each order
  - `pizza_id` – Unique pizza identifier
  - `pizza_name` – Name of the pizza
  - `category` – Pizza type (Veg, Non-Veg, Special)
  - `size` – Small, Medium, Large, XL
  - `order_date` – Date of order placement
  - `quantity` – Number of pizzas ordered
  - `total_price` – Total cost of the order
  - `customer_id` – Unique customer identifier
  - `payment_method` – Cash, Card, Wallet, etc.

---

## SQL Insights & Trends
SQL queries were used to analyze **key performance indicators (KPIs), sales trends, and pizza performance.**  

- **Business KPIs:** Total revenue, average order value, total pizzas sold, and order volume.  
- **Sales Trends:** Identified daily and monthly order patterns to analyze peak sales periods.  
- **Revenue Breakdown:** Measured sales by pizza category and size to determine best-selling items.  
- **Pizza Performance:** Ranked pizzas based on revenue, quantity sold, and total orders.  
- **Customer Order Patterns:** Analyzed top-performing and least-ordered pizzas to optimize menu strategies.  

These SQL-based insights provided a foundation for visualizing trends in Power BI.

---

## Data Cleaning & Transformation in Power BI
Data was **cleaned and transformed** using **Power Query & DAX**.

### **Data Cleaning Steps:**
- Removed duplicates and handled missing values.  
- Standardized date formats and extracted key date components (Month, Year, Weekday).  
- Categorized pizzas and ensured uniform naming conventions.

### **DAX Calculations in Power BI**
- **Total Revenue:** Sum of all sales.  
- **Average Order Value (AOV):** Revenue per order.  
- **Monthly Sales Growth:** Percentage increase in revenue month-over-month.  
- **Total Orders Count:** Count of unique orders placed.  
- **Revenue by Category:** Total sales based on pizza type.  

These transformations helped in creating interactive and insightful dashboards.

---

## Power BI Dashboards & Insights
The **Power BI dashboard** provides interactive visualizations for:

1. **Sales Trends Over Time** – Monthly and yearly sales growth.
2. **Best-Selling Pizza Types** – Identifies the most popular pizzas.
3. **Customer Spending Patterns** – Top customers by total orders.
4. **Revenue Breakdown** – Sales by pizza category and size.
5. **Order Volume Analysis** – Trends in order frequency.
6. **Profitability Metrics** – Average order value and revenue per category.

