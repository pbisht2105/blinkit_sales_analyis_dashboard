# Blinkit Sales Performance Analysis
![blinkit Project cover](https://github.com/pbisht2105/blinkit_sales_analyis_dashboard/blob/main/Blinkit%20sales%20cover%20image.png)

## Table of Contents

- [Project Overview](#project-overview)
- [What is this project?](#what-is-this-project)
- [Data Set Used](#data-set-used)
- [Key Business Problems & KPIs](#key-business-problems--kpis)
- [Chart Requirements & Objectives](#chart-requirements--objectives)
- [Process](#process)
- [Dashboard](#dashboard)
- [Insights & Recommendations](#insights--recommendations)
- [Final Conclusion](#final-conclusion)


## Project Overview
This project focuses on analyzing Blinkit's sales performance, customer satisfaction, and inventory distribution. The goal is to identify key insights and opportunities for optimization using **Power BI**. By importing data Blinkit Grocery Data file into Power BI, this analysis provides a comprehensive view of Blinkit's sales, item performance, customer ratings, and outlet performance across different KPIs.

---

## What is this project?
The project aims to conduct an in-depth analysis of Blinkit’s sales data to help optimize sales performance, customer satisfaction, and inventory distribution. Through **Power BI** visualizations, the project answers critical business questions, tracks KPIs, and delivers insights into sales trends, item performance, and outlet-related metrics.

---

## Data Set Used
The data for this project is sourced from the internal Blinkit sales dataset [Blinkit Dataset](https://github.com/pbisht2105/blinkit_sales_analyis_dashboard/blob/main/BlinkIT%20Grocery%20Data.xlsx).

- **Dataset Details**: 
  - The dataset includes transaction-level data for all items sold by Blinkit.
  - Key fields include `item_id`, `item_type`, `fat_content`, `total_sales`, `item_quantity`, `customer_rating`, `outlet_id`, `outlet_size`, `outlet_location`, and `outlet_establishment_type`.

The data is imported into **Power BI** from the Blinkit Grocery Data file, where various KPIs and charts are generated for analysis.

---

## Key Business Problems & KPIs

### Business Problems Addressed:
- **Sales Performance**: How well are different items performing in terms of total sales?
- **Customer Satisfaction**: How does the customer rating of items affect their sales?
- **Inventory Distribution**: How do different outlet characteristics (size, location, establishment type) impact sales performance?
- **Optimization Opportunities**: Where can Blinkit optimize its operations to increase sales, improve customer satisfaction, and streamline inventory distribution?

### KPIs Generated:
1. **Total Sales**: The overall revenue generated from all items sold.
2. **Average Sales**: The average revenue per sale.
3. **Number of Items**: The total count of different items sold.
4. **Average Rating**: The average customer rating for items sold.

---

## Chart Requirements & Objectives

### 1. Total Sales by Fat Content
- **Objective**: Analyze the impact of fat content on total sales.
- **Additional KPIs**: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.
- **Chart Type**: **Donut Chart**.

### 2. Total Sales by Item Type
- **Objective**: Identify the performance of different item types in terms of total sales.
- **Additional KPIs**: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with item types.
- **Chart Type**: **Bar Chart**.

### 3. Fat Content by Outlet for Total Sales
- **Objective**: Compare total sales across different outlets segmented by fat content.
- **Additional KPIs**: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.
- **Chart Type**: **Stacked Column Chart**.

### 4. Total Sales by Outlet Establishment
- **Objective**: Evaluate how the age or type of outlet establishment influences total sales.
- **Chart Type**: **Line Chart**.

### 5. Sales by Outlet Size
- **Objective**: Analyze the correlation between outlet size and total sales.
- **Chart Type**: **Donut/Pie Chart**.

### 6. Sales by Outlet Location
- **Objective**: Assess the geographic distribution of sales across different locations.
- **Chart Type**: **Funnel Map**.

### 7. All Metrics by Outlet Type
- **Objective**: Provide a comprehensive view of all key metrics (Total Sales, Average Sales, Number of Items, Average Rating) broken down by different outlet types.
- **Chart Type**: **Matrix Card**.

---

## Process

### 1. Data Import & Preprocessing in Power BI
   The raw sales data is imported into Power BI from Blinkit Grocery Data file. This data includes transactional details like `item_id`, `fat_content`, `item_type`, `total_sales`, and `customer_rating`. The data is cleaned and preprocessed in Power BI to ensure accurate calculations and visualizations.

### 2. Data Aggregation & KPI Calculation
   The following key performance indicators (KPIs) are calculated:
   - **Total Sales**: Sum of all sales transactions.
   - **Average Sales**: Average of all sales transactions.
   - **Number of Items**: Count of distinct items sold.
   - **Average Rating**: Average customer rating across all items.

### 3. Visualizing Insights in Power BI
   A range of charts are created to answer key business questions, such as:
   - **Total Sales by Fat Content**: A donut chart showing how fat content impacts total sales.
   - **Sales by Item Type**: A bar chart displaying the sales performance of different item types.
   - **Fat Content by Outlet for Total Sales**: A stacked column chart to compare total sales segmented by fat content across outlets.
   - **Sales by Outlet Location**: A funnel map illustrating geographic sales distribution.

### 4. Dashboard Creation
   These visualizations are combined in a Power BI dashboard that provides a comprehensive, interactive view of the sales data. Users can explore the data by interacting with filters based on outlet type, fat content, item type, and location.

---

## Dashboard

Here is a screenshot of the Power BI dashboard showing various visualizations related to Blinkit's sales performance:

![Power BI Dashboard Screenshot](https://github.com/pbisht2105/blinkit_sales_analyis_dashboard/blob/main/Blinkit%20Sales%20Dashboard.png)  

### Key Features of the Dashboard:
- **Total Sales by Fat Content**: Donut chart showing sales distribution based on fat content.
- **Total Sales by Item Type**: Bar chart highlighting top-performing item types.
- **Fat Content by Outlet**: Stacked column chart comparing sales across outlets by fat content.
- **Sales Distribution by Outlet Location**: Funnel map representing geographic distribution of sales.
- **All Metrics by Outlet Type**: Matrix card displaying KPIs (Total Sales, Average Sales, Number of Items, Average Rating) by outlet type.

---

## Insights & Recommendations

### 1. Sales Performance Insights:
   - **Top Item Types**: Certain item types show higher sales performance, suggesting that Blinkit can optimize its inventory or marketing around these products.
   - **Fat Content Trends**: Fat content plays a significant role in driving sales, with lower-fat items showing better sales in certain outlets.

### 2. Outlet Optimization:
   - **Outlet Size vs. Sales**: Larger outlets tend to generate higher sales, suggesting that Blinkit should focus on optimizing larger outlets for better inventory distribution and sales performance.
   - **Outlet Location Trends**: Certain geographic locations perform better than others, suggesting that Blinkit can optimize its marketing efforts in these locations.

### 3. Customer Satisfaction:
   - **Rating Trends**: Items with higher ratings tend to perform better in terms of total sales and customer satisfaction, indicating that Blinkit should focus on improving customer satisfaction for underperforming products.

---

## Final Conclusion

This project provides critical insights into Blinkit's sales performance, customer satisfaction, and outlet optimization. By leveraging **Power BI**, Blinkit can make data-driven decisions to enhance sales, improve customer experiences, and streamline operations. Future recommendations include:
- **Focusing on High-Rating Items**: Promote products with higher customer ratings to increase sales.
- **Optimizing Sales in Key Locations**: Use geographic insights to target marketing efforts in high-performing locations.
- **Outlets Optimization**: Streamline operations in larger outlets to ensure better performance.
