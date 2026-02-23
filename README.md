 Pizza Sales Analysis Project | SQL + Power BI

 Project Overview

This project analyzes a pizza store’s sales data to understand business performance, customer preferences, and revenue trends. The goal is to convert raw sales data into meaningful insights using SQL for data analysis and Power BI for visualization.

This is a complete end-to-end data analytics project covering data extraction, transformation, KPI calculation, and dashboard creation**.

---

 Problem Statement

The business wants to analyze pizza sales performance to answer key questions:

* What is the total revenue generated?
* How many orders and pizzas were sold?
* Which pizza categories and sizes perform best?
* What are the daily and monthly sales trends?
* Which pizzas are top and bottom sellers?

The analysis helps the business understand customer behavior and improve decision-making.

---

 KPI Requirements

The following key performance indicators (KPIs) were calculated:

Total Revenue** → Sum of total sales amount
Average Order Value** → Revenue ÷ Total Orders
Total Pizzas Sold** → Total quantity sold
Total Orders** → Number of orders placed
Average Pizzas per Order** → Quantity ÷ Orders

---

 Chart Requirements Implemented

 Sales Trend Analysis

* Daily trend of total orders (Bar Chart)
* Monthly trend of total orders (Line Chart)

 Sales Distribution Analysis

* Percentage of sales by pizza category (Pie Chart)
* Percentage of sales by pizza size (Pie Chart)

 Performance Analysis

* Total pizzas sold by category (Funnel Chart)
* Top 5 pizzas by revenue, quantity, and orders (Bar Chart)
* Bottom 5 pizzas by revenue, quantity, and orders (Bar Chart)

---

 Dataset Description

The dataset contains 4 related tables:

Orders** → Order ID, Date, Time
Order Details** → Quantity and pizza ID
Pizzas** → Pizza size and price
Pizza Types** → Category and pizza names

These tables were connected using primary and foreign keys.

---

 Project Procedure

 Step 1: Data Preparation (Excel)

* Imported raw dataset
* Verified data quality
* Prepared tables for analysis

---

 Step 2: SQL Analysis

Performed the following steps:

1. Created database and imported tables
2. Explored table relationships
3. Joined multiple tables using keys
4. Calculated KPIs:

   * Total Revenue
   * Total Orders
   * Total Quantity Sold
5. Analyzed:

   * Sales trends by date
   * Sales by category and size
   * Top and bottom selling pizzas

---

 Step 3: Power BI Dashboard Creation

1. Imported SQL dataset into Power BI
2. Created table relationships
3. Built DAX measures for KPIs
4. Designed interactive visuals:

   * KPI Cards
   * Trend charts
   * Pie charts
   * Bar charts
   * Funnel chart

---

Business Value Created

This analysis helps the pizza business:

* Identify best-selling products
* Understand customer preferences
* Improve inventory planning
* Optimize pricing strategies
* Increase overall profitability

---

 Key Insights Generated

* Classic category pizzas generate the highest revenue
* Large size pizzas are most frequently ordered
* Sales peak during weekends and evening hours
* Few pizzas contribute to most of the revenue

---

 Tools & Technologies Used

SQL** → Data analysis and KPI calculation
Power BI** → Data visualization and dashboard
Excel** → Data storage and preprocessing

---

 Dashboard

Power BI dashboard screenshots are included in this repository.

---

 Conclusion

This project demonstrates how SQL and Power BI can be used together to transform raw sales data into meaningful business insights. It showcases practical data analytics skills such as querying, KPI analysis, and interactive dashboard creation.

---

 Outcomes

Through this project, I learned:

* Writing real-world SQL queries
* Performing business KPI analysis
* Creating professional Power BI dashboards
* Communicating insights effectively

---
