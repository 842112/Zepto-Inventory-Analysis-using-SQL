# Zepto-Inventory-Analysis-using-SQL
**Zepto Inventory Analysis using SQL:** Performed data cleaning and analysis on Zepto’s product and inventory data using SQL to uncover insights on pricing, stock availability, and revenue trends. Enabled data-driven decisions through structured queries and inventory performance metrics.

Here’s a complete and professional **project description** for your **Zepto Inventory Analysis (SQL)** project, following the structure you've provided. This version is ideal for including in your resume portfolio, LinkedIn, GitHub README, or for interview discussions.

---

## 📌 **Project Title:**

**Zepto Inventory Analysis using PostgreSQL**

---

## 💡 **Brief One Line Summary:**

Performed data cleaning and exploratory analysis on Zepto's product and inventory data using SQL to uncover actionable business insights and optimize inventory decisions.

---

## 🧾 **Overview:**

This project involved analyzing inventory and pricing data for Zepto, a fast-growing online grocery and quick-commerce platform. Using raw product-level data, the goal was to identify patterns in pricing, discount strategies, stock availability, and category-wise performance. The project focused on transforming unclean data into structured insights for better decision-making using PostgreSQL.

---

## ❓ **Problem Statement:**

Zepto manages a wide range of products with varying prices, discounts, and availability status. The dataset contained inconsistencies like zero-priced items, duplicate entries, and unclear categorization. The challenge was to:

* Clean and prepare the data.
* Analyze discount trends and stock patterns.
* Derive meaningful insights that can improve pricing and restocking strategies.

---

## 📂 **Dataset:**

* File: `zepto_v2.csv`
* Fields include: `sku_id`, `name`, `category`, `mrp`, `discountPercent`, `discountedSellingPrice`, `weightInGms`, `availableQuantity`, `outOfStock`, and `quantity`.

---

## 🛠 **Tools and Technologies:**

* **Database:** PostgreSQL
* **Query Language:** SQL
* **Environment:** pgAdmin / DBeaver / PostgreSQL CLI
* **Data Types:** Numeric, Integer, Boolean, Varchar

---

## ⚙️ **Methods:**

1. **Table Creation**: Designed a normalized table schema in PostgreSQL to store and query the dataset efficiently.
2. **Data Cleaning**:

   * Removed rows with `MRP = 0` or `Discounted Selling Price = 0`.
   * Converted price from paise to rupees.
   * Identified and handled null values.
   * Removed duplicates.
3. **Exploratory Analysis**:

   * Analyzed product categories, duplicates, and out-of-stock status.
   * Computed revenue and inventory metrics using SQL queries.
4. **Feature Engineering**:

   * Derived price-per-gram metric.
   * Grouped products based on weight: Low, Medium, Bulk.
5. **Business Insights**:

   * Identified high MRP out-of-stock products.
   * Ranked top discounted products.
   * Estimated category-wise revenue and inventory weight.

---

## 🔍 **Key Insights:**

* Top 10 products offered discounts above 50%, ideal for promotional campaigns.
* High-MRP products (₹500+) with <10% discounts were underperforming.
* Most out-of-stock products were high in MRP, indicating demand-supply mismatch.
* Category-wise revenue showed significant variation, with some underutilized segments.
* Weight-based categorization helped classify products for logistics optimization.

---

## 📊 **Dashboard/Model/Output:**

This was a **SQL-based analytical project** (no GUI dashboard), but the outputs included:

* Aggregated tables for revenue, discounts, and inventory weight.
* Insightful result sets from structured queries.
* Can be integrated into Power BI for visualization if needed.

---

## ▶️ **How to Run this Project?**

1. Import `zepto_v2.csv` into a PostgreSQL environment.
2. Use the SQL script `Zepto_SQL_data_analysis.sql` to:

   * Create table and load data.
   * Clean and process the data.
   * Run analytical queries for insights.
3. Optional: Export result sets to CSV for visualization in Power BI or Excel.

---

## 📈 **Results & Conclusion:**

The project successfully demonstrated how SQL can be used not just for querying data but also for:

* Cleaning real-world datasets.
* Building scalable analysis pipelines.
* Generating clear, actionable business insights.
  These insights can help Zepto streamline restocking processes, re-evaluate pricing strategies, and prioritize categories that drive revenue.

