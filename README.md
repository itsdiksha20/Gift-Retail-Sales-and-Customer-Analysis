# Gift Retail Sales & Customer Analysis

## Project Overview

This is a practice data analysis project focused on analyzing gift retail sales data to understand sales performance, customer spending, product performance, delivery efficiency, and order patterns.

The project was completed as a learning exercise to practice **Google Sheets/Excel-based data cleaning, data analysis, Pivot Tables, formulas, and dashboard development**.

### Key Objectives

* Analyze overall sales and order performance
* Identify high-performing products and categories
* Analyze customer spending and order volume
* Identify monthly and occasion-based sales trends
* Analyze order distribution across cities
* Examine the relationship between order quantity and delivery duration
* Build an interactive sales dashboard

---

## Dataset

The project uses three datasets:

### Customer Data

* **Rows:** 100
* **Columns:** 7
* **Key Features:** Customer ID, Customer Name, City, Contact Number, Email, Gender, Address

### Product Data

* **Rows:** 70
* **Columns:** 6
* **Key Features:** Product ID, Product Name, Category, Price, Occasion, Description

### Orders Data

* **Rows:** 1,000
* **Columns:** 10
* **Key Features:** Order ID, Customer ID, Product ID, Quantity, Order Date, Order Time, Delivery Date, Delivery Time, Location, Occasion

---

## Data Preparation & EDA

The following data preparation steps were performed:

* Checked dataset structure and key fields
* Verified primary key uniqueness
* Validated Customer ID and Product ID relationships
* Checked for missing values
* Checked for duplicate orders
* Corrected data types for numeric, date, and time fields
* Checked data consistency and validity
* Combined customer and product information with order-level data

### Feature Engineering

Created additional features for analysis:

* **Revenue:** Calculated using Quantity × Product Price
* **Delivery Duration:** Calculated using order and delivery date/time
* **Order Month:** Created in `YYYY-MM` format for monthly sales analysis

---

## Business Questions

The analysis focused on the following business questions:

1. What is the total revenue generated?
2. What is the average order value and average delivery time?
3. How does monthly sales performance vary?
4. Which products generate the highest revenue?
5. Which customers contribute the most revenue?
6. What are the Top 5 products by revenue?
7. Which cities have the highest number of orders?
8. Is there a relationship between order quantity and delivery duration?
9. Which occasions generate the highest revenue?
10. How does product performance vary across occasions?

---

## Analysis & Key Findings

### Overall Performance

* **Total Orders:** 1,000
* **Total Revenue:** ₹3,520,984
* **Average Order Value:** ₹3,520.98
* **Average Delivery Duration:** 5.50 days

### Category Performance

**Colors** generated the highest category revenue at **₹1,005,645**, followed by **Soft Toys (₹740,831)** and **Sweets (₹733,842)**.

### Monthly Performance

**August** recorded the highest monthly revenue at **₹737,389**, followed by **February (₹704,509)** and **March (₹511,823)**.

### Product Performance

**Magnam Set** was the highest-revenue product, generating **₹121,905**.

The Top 5 products by revenue were identified through product-level revenue aggregation.

### Customer Performance

The analysis identified the **Top 10 customers by revenue** to highlight high-value customers.

### City Performance

The analysis identified the **Top 10 cities by order volume**, with **Dhanbad, Kavali, and Haridwar** among the highest-order cities.

### Occasion Performance

**Anniversary** generated the highest revenue at **₹674,634**, followed by **Raksha Bandhan (₹631,585)** and **All Occasions (₹586,176)**.

### Quantity vs Delivery Duration

The correlation between order quantity and delivery duration was **0.00415**, indicating no meaningful linear relationship between the two variables in this dataset.

---

## Dashboard

An interactive dashboard was created to provide a consolidated view of the analysis.

### Dashboard Includes

**KPIs**

* Total Orders
* Total Revenue
* Average Order Value
* Average Delivery Time

**Visualizations**

* Revenue by Category
* Top 5 Products by Revenue
* Top 10 Customers by Revenue
* Revenue by Month
* Revenue by Occasion
* Top 10 Cities by Orders

**Filters**

* Occasion
* Category

### Dashboard Preview

![Gift Retail Sales & Customer Analysis Dashboard](Dashboard.pdf)

---

## Tools & Skills Used

* Google Sheets
* Pivot Tables
* XLOOKUP
* QUERY
* CORREL
* Data Cleaning
* Data Validation
* Feature Engineering
* KPI Analysis
* Trend Analysis
* Dashboard Development
* Business Analysis

---

## Business Recommendations

* Prioritize high-performing categories such as **Colors, Soft Toys, and Sweets** for promotional and inventory planning.
* Strengthen campaigns around high-revenue occasions such as **Anniversary, Raksha Bandhan, and Holi**.
* Analyze high-performing months such as **August and February** to understand the products and occasions contributing to higher sales.
* Use the Top 10 customer analysis to support targeted retention and repeat-purchase strategies.
* Monitor high-order-volume cities such as **Dhanbad, Kavali, and Haridwar** for potential market opportunities.
* Since order quantity showed almost no linear relationship with delivery duration, investigate other factors such as location, product, or occasion when analyzing delivery performance.

---

## Project Documentation

Detailed project documentation covering the data preparation, EDA, analysis, insights, dashboard, and recommendations is included in the project files.

---

## Dataset Source & Project Note

This is a **practice/learning project**.

The dataset is a practice dataset based on a publicly available FNP gift-sales analysis dataset.

The raw dataset is not my original creation. The data cleaning, preparation, analysis, calculations, and dashboard development were performed independently as part of my learning and practice in data analytics.

The project is intended to demonstrate my practical understanding of spreadsheet-based data analysis and dashboard development.
