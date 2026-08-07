# 🍕 Pizza Sales SQL Analysis & Power BI Dashboard

## 📌 Project Overview

This project analyzes pizza sales data using **MySQL** and **Power BI** to identify key business insights related to sales, revenue, customer ordering patterns, pizza categories, sizes, and product performance.

The project includes SQL-based data analysis and an interactive Power BI dashboard that helps visualize important sales trends and business KPIs.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze overall pizza sales performance
* Calculate total revenue generated
* Identify the most frequently ordered pizza sizes
* Find the highest-priced pizzas
* Identify the top-selling pizza types
* Analyze sales by pizza category
* Understand ordering patterns by hour and date
* Calculate revenue contribution by pizza type and category
* Identify the top-performing pizzas based on revenue
* Create an interactive dashboard for business insights

---

## 🛠️ Tools & Technologies

| Tool                     | Purpose                                   |
| ------------------------ | ----------------------------------------- |
| **MySQL**                | Data analysis and SQL queries             |
| **MySQL Workbench**      | Writing and executing SQL queries         |
| **Power BI**             | Interactive dashboard and visualization   |
| **DAX**                  | Measures and calculated columns           |
| **Microsoft PowerPoint** | Project presentation                      |
| **GitHub**               | Project documentation and version control |

---

## 📂 Project Structure

```text
Pizza-Sales-SQL-Analysis/
│
├── README.md
│
├── SQL/
│   └── Pizza_Sales_Analysis.sql
│
├── Dataset/
│   ├── pizza_types.csv
│   ├── pizzas.csv
│   ├── orders.csv
│   └── order_details.csv
│
├── PowerBI/
│   └── Pizza_Sales_Dashboard.pbix
│
└── Report/
    └── Pizza_Sales_Project_Report.pdf
```

---

## 🗃️ Dataset

The project uses four main tables:

### 1. `pizza_types`

Contains information about different pizza types.

**Important columns:**

* `pizza_type_id`
* `name`
* `category`
* `ingredients`

### 2. `pizzas`

Contains pizza size and pricing information.

**Important columns:**

* `pizza_id`
* `pizza_type_id`
* `size`
* `price`

### 3. `orders`

Contains order-level information.

**Important columns:**

* `order_id`
* `order_date`
* `order_time`

### 4. `order_details`

Contains individual pizza items included in each order.

**Important columns:**

* `order_details_id`
* `order_id`
* `pizza_id`
* `quantity`

---

## 🔍 SQL Analysis

The SQL analysis answers several business questions.

### Basic Analysis

* What is the total number of orders?
* What is the total revenue generated?
* What is the highest-priced pizza?
* What is the most common pizza size ordered?
* What are the top 5 most ordered pizza types?

### Intermediate Analysis

* What is the total quantity of pizzas ordered by category?
* How are orders distributed throughout the day?
* What is the category-wise distribution of pizzas?
* What is the average number of pizzas ordered per day?
* Which pizza types generate the most revenue?

### Advanced Analysis

* What percentage of total revenue does each pizza type contribute?
* What is the cumulative revenue over time?
* What are the top 3 pizza types by revenue within each category?

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard was created to visualize the results of the SQL analysis.

### Key KPIs

* 💰 Total Revenue
* 🧾 Total Orders
* 🍕 Total Pizzas Sold
* 💵 Average Pizza Price
* 🏆 Highest Pizza Price

### Dashboard Analysis

The dashboard provides insights into:

* Revenue performance
* Order volume
* Pizza category performance
* Pizza size distribution
* Top-selling pizzas
* Revenue by pizza type
* Revenue by category
* Ordering trends by time
* Pizza quantity analysis

### Interactive Features

The dashboard includes:

* **Category slicer**
* **Pizza size slicer**
* Interactive charts
* KPI cards
* Tables and matrices
* Page navigation
* Cross-filtering between visuals

Selecting a category or pizza size dynamically updates the visuals across the dashboard pages.

---

## 📈 Key Insights

The analysis helps answer important business questions such as:

* Which pizza categories generate the highest revenue?
* Which pizza sizes are ordered most frequently?
* Which pizza types are the best sellers?
* Which pizzas generate the highest revenue?
* During which hours are the most orders placed?
* How does revenue change over time?
* Which pizza categories have the highest demand?

These insights can help a pizza business understand customer preferences and make better decisions regarding pricing, inventory, promotions, and product offerings.

---

## 🧮 Example SQL Analysis

Example calculation for total revenue:

```sql
SELECT 
    ROUND(SUM(order_details.quantity * pizzas.price), 2) AS total_revenue
FROM order_details
JOIN pizzas 
    ON order_details.pizza_id = pizzas.pizza_id;
```

Example calculation for total orders:

```sql
SELECT 
    COUNT(DISTINCT order_id) AS total_orders
FROM orders;
```

---

## 📊 Dashboard Preview

Add screenshots of your Power BI dashboard here.

```text
![Pizza Sales Dashboard](PowerBI/dashboard_preview.png)
```

You can replace `dashboard_preview.png` with the actual screenshot file you upload to GitHub.

---

## 📁 Files Included

### SQL

`Pizza_Sales_Analysis.sql`

Contains all SQL queries used to analyze the pizza sales dataset.

### Dataset

Contains the CSV files used for the analysis:

* `pizza_types.csv`
* `pizzas.csv`
* `orders.csv`
* `order_details.csv`

### Power BI

`Pizza_Sales_Dashboard.pbix`

Contains the interactive Power BI dashboard, including:

* Data model
* DAX measures
* Calculated columns
* Charts
* KPI cards
* Slicers
* Dashboard formatting

### Report

`Pizza_Sales_Project_Report.pdf`

Contains the detailed project report and analysis.

---

## 🚀 How to Use This Project

### Step 1: Download the Repository

Clone or download this repository from GitHub.

### Step 2: Load the Dataset

Import the CSV files into MySQL.

### Step 3: Run SQL Queries

Open:

```text
SQL/Pizza_Sales_Analysis.sql
```

Run the queries in MySQL Workbench to reproduce the analysis.

### Step 4: Open Power BI Dashboard

Open:

```text
PowerBI/Pizza_Sales_Dashboard.pbix
```

If required, update the data source connection.

### Step 5: Explore the Dashboard

Use the slicers and interactive visuals to explore pizza sales performance.

---

## 💡 Business Value

This project demonstrates how raw sales data can be transformed into meaningful business insights using **SQL, data modeling, DAX, and Power BI**.

The analysis can help management:

* Identify best-selling products
* Understand customer preferences
* Optimize product offerings
* Monitor revenue performance
* Identify peak ordering periods
* Improve inventory planning
* Support data-driven decision making

---

## 👩‍💻 Author

**Unnati Sonwane**

Aspiring Data Analyst

### Skills Demonstrated

* SQL
* MySQL
* Power BI
* DAX
* Data Analysis
* Data Visualization
* Data Cleaning
* Business Intelligence
* Dashboard Development

---

## ⭐ Project Highlights

**SQL Analysis → Data Modeling → DAX → Power BI Dashboard → Business Insights**

This project demonstrates an end-to-end data analytics workflow from raw data to an interactive business intelligence dashboard.

---

## 📌 Future Improvements

Possible future enhancements include:

* Adding sales forecasting
* Adding customer segmentation
* Adding profit and cost analysis
* Adding monthly and yearly comparisons
* Adding advanced KPI tracking
* Adding automated data refresh
* Deploying the dashboard to Power BI Service
