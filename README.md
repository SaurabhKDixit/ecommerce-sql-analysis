# E-Commerce Sales & Customer Analytics (SQL)

## 📌 Project Overview
This project analyzes an e-commerce company's sales data using SQL to uncover revenue trends, customer behavior, and product performance.  
The goal is to demonstrate strong **SQL fundamentals**, **data cleaning**, and **business-oriented analysis**, suitable for **entry-level data analyst roles**.

---

## 🎯 Objectives
- Clean and prepare raw sales data
- Analyze revenue and sales trends
- Identify top products and high-value customers
- Segment customers based on purchasing behavior
- Provide actionable business insights and recommendations

---

## 🛠 Tools & Technologies
- **Database:** MySQL
- **Language:** SQL
- **Dataset:** Online Retail Dataset (Kaggle)
- **Version Control:** Git & GitHub

---

## 📂 Dataset
**Source:** https://www.kaggle.com/datasets/carrie1/ecommerce-data  

The dataset contains transactional data including:
- Invoice number
- Product details
- Quantity sold
- Price
- Invoice date
- Customer ID
- Country

---

## 🧱 Database Schema
A single main table is used after cleaning:

`sales_cleaned`
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country
- TotalSales

---

## ❓ Business Questions Answered
1. What is the total revenue generated?
2. How does revenue change over time (monthly trends)?
3. Which products sell the most?
4. Who are the top revenue-generating customers?
5. Which countries generate the most revenue?
6. How can customers be segmented by value?
7. How many customers are repeat buyers?

---

## 📊 Key Insights
- A small percentage of customers contribute a large portion of revenue
- Sales show clear seasonality across months
- The UK is the highest revenue-generating country
- High-value customers should be prioritized for retention

---

## 💡 Recommendations
- Launch loyalty programs for high-value customers
- Increase inventory for top-selling products
- Run targeted promotions during low-sales months

---

## ▶️ How to Run This Project
1. Create a MySQL database
2. Run SQL files in order from the `/sql` folder
3. Import the CSV dataset
4. Execute analysis queries

---

## 📁 Project Structure
