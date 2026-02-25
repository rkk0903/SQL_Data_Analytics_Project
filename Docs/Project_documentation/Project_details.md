# 📊 SQL Data Analysis Project — Documentation

## 🎯 Objective
The objective of this project is to build an end-to-end SQL data analysis system using a modern data warehouse architecture and perform analytical reporting.

---

## 🧭 Step 1 — Dataset Understanding
Initial analysis of source data to identify:

- CRM_source
- ERP_source

Purpose:
- Understand relationships
- Plan data model

---

## 🥉 Step 2 — Bronze Layer (Raw Data)
Raw datasets were imported into SQL tables without modifications.

Tables:
- bronze.crm_cust_info
- bronze.crm_prd_info
- bronze.crm_sales_details
- bronze.erp_cust_az12
- bronze.erp_loc_a101
- bronze.erp_px_cat_g1v2

Purpose:
- Preserve raw data
- Maintain data lineage

---

## 🥈 Step 3 — Silver Layer (Cleaning & Transformation)
Data cleaning and transformation performed:

- Data type corrections
- Null value handling
- Duplicate removal
- Data standardization

Output tables:
- silver.crm_cust_info
- silver.crm_prd_info
- silver.crm_sales_details
- silver.erp_* tables

---

## 🥇 Step 4 — Gold Layer (Analytics Model)

A Star Schema model was created.

### Fact Table
- fact_sales

### Dimension Tables
- dim_customers
- dim_products

Purpose:
- Optimized analytical queries
- Reporting-ready structure

---

## ⚙️ Step 5 — ETL Process

### Extract
Load raw files into Bronze tables.

### Transform
Apply cleaning logic and business rules in Silver layer.

### Load
Populate Gold layer fact & dimension tables.

---

## 📊 Step 6 — Exploratory Analysis

Scripts performed:

- Database exploration
- Dimension analysis
- Data range exploration
- Measure analysis

Purpose:
- Validate data quality
- Understand patterns

---

## 📈 Step 7 — Advanced Analytical SQL

Analysis performed:

- Magnitude Analysis
- Ranking Analysis
- Change Over Time Analysis
- Cumulative Analysis
- Performance Analysis
- Data Segmentation
- Part-to-Whole Analysis

SQL Concepts Used:
- Window functions
- CTEs
- Aggregations
- CASE expressions

---

## 📑 Step 8 — Reporting

Generated reporting tables:

- report_customers
- report_products

These provide business insights for decision making.

---

### Customer KPIs
- Recency
- Total Sales
- Total Orders
- Average Order Value
- Average Monthly Spend

### Product KPIs
- Total Sales
- Total Quantity Sold
- Average Order Revenue
- Average Monthly Revenue
## 🏗 Project Structure

Project/
- │
- ├── Datasets (Bronze, Silver, Gold)
- └── Scripts (SQL analysis files)

  
---

## 🎯 Final Outcome

- End-to-end ETL pipeline created
- Modern data warehouse design implemented
- Analytical reporting generated using SQL

---

## 🧠 Key Learnings

- Data warehouse architecture
- ETL pipeline development
- SQL analytics
- Star schema modelling
