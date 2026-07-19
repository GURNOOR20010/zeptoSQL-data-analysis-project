# zeptoSQL-data-analysis-project
# 🛒 Zepto Inventory Data Analysis using SQL

## 📌 Project Overview

This project analyzes a **Zepto grocery products dataset** using SQL. The analysis includes data exploration, data cleaning, and business insights to understand product pricing, discounts, inventory, and category-wise performance.

The project demonstrates practical SQL skills such as filtering, aggregation, grouping, sorting, CASE statements, and data cleaning.

---

## 📂 Dataset Information

The dataset contains product information including:

- SKU ID
- Product Category
- Product Name
- MRP
- Discount Percentage
- Available Quantity
- Discounted Selling Price
- Product Weight (grams)
- Stock Status
- Quantity

---

## 🛠 Technologies Used

- PostgreSQL
- SQL

---

## 📋 Database Schema

| Column | Data Type |
|----------|-----------|
| sku_id | SERIAL |
| category | VARCHAR(120) |
| name | VARCHAR(150) |
| mrp | NUMERIC(8,2) |
| discountPercent | NUMERIC(5,2) |
| availableQuantity | INTEGER |
| discountedSellingPrice | NUMERIC(8,2) |
| weightInGms | INTEGER |
| outOfStock | BOOLEAN |
| quantity | INTEGER |

---

# 📊 Project Workflow

## 1. Data Exploration

Performed exploratory analysis by:

- Counting total records
- Viewing sample data
- Detecting NULL values
- Listing unique product categories
- Checking stock availability
- Finding duplicate product names

---

## 2. Data Cleaning

Data preprocessing steps included:

- Removing products with zero MRP
- Converting prices from paise to rupees
- Validating cleaned data

---

## 3. Business Analysis

The following business questions were answered:

### ✅ Top 10 Best Value Products
Identified products with the highest discount percentage.

---

### ✅ High MRP Products that are Out of Stock
Found premium products currently unavailable.

---

### ✅ Estimated Revenue by Category
Calculated revenue using:

Revenue = Discounted Selling Price × Available Quantity

---

### ✅ Premium Products with Low Discounts
Listed products with:

- MRP > ₹500
- Discount < 10%

---

### ✅ Categories with Highest Average Discounts
Calculated average discount percentage for every category.

---

### ✅ Price Per Gram Analysis
Computed price per gram for products weighing at least 100 grams to identify better value products.

---

### ✅ Product Weight Classification
Classified products into:

- Low (<1000g)
- Medium (<5000g)
- Bulk (5000g and above)

using SQL CASE statements.

---

### ✅ Total Inventory Weight per Category
Calculated total inventory weight available for each category.

---

# 📈 SQL Concepts Used

- CREATE TABLE
- DROP TABLE
- SELECT
- DISTINCT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- COUNT()
- SUM()
- AVG()
- ROUND()
- UPDATE
- DELETE
- CASE Statement
- Aggregate Functions

---

# 📁 Project Structure

```
Zepto_SQL_Project/
│
├── zepto.sql          # Complete SQL script
├── dataset.csv        # Zepto dataset
└── README.md          # Project documentation
```

---

# 🎯 Learning Outcomes

This project helped strengthen practical SQL skills including:

- Database creation
- Data exploration
- Data cleaning
- Business data analysis
- Aggregate functions
- Conditional logic using CASE
- Inventory analysis
- Revenue calculation
- Writing optimized SQL queries

---

## 🚀 Future Improvements

- Create SQL Views for reusable reports
- Add Stored Procedures
- Implement Triggers for inventory updates
- Build interactive dashboards using Power BI or Tableau
- Connect the database to Python for advanced analysis

---

## 👨‍💻 Author

**Gurnoor Singh Arora**



---
⭐ If you found this project useful, consider giving it a star on GitHub!
