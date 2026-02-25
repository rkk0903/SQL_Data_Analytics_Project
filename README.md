# SQL_Data_Analytics_Project
Modern SQL analytics repository featuring real-world analytical patterns such as time-based trend analysis, cumulative metrics, performance measurement, segmentation, and part-to-whole insights

# 📊 SQL Data Analysis Project

## 📌 Overview
This project demonstrates an **end-to-end SQL Data Analytics pipeline** using a modern **Data Warehouse architecture** (Bronze → Silver → Gold).

The project covers data ingestion, ETL processing, data modelling, analytical SQL queries, and report generation using sales, customer, and product data.

---

## 🏗 Architecture

### 🥉 Bronze Layer
Raw data imported without modifications.

### 🥈 Silver Layer
Data cleaning and transformation:
- Data type corrections
- Null handling
- Standardization

### 🥇 Gold Layer
Business-ready analytical model:
- Fact and Dimension tables
- Reporting datasets

---

## 🗂 Project Structure
SQL PROJECT/
│
├── Data-Analysis_project/
│   ├── Datasets/
│   │   ├── bronze.*
│   │   ├── silver.*
│   │   └── gold.*
│   │
│   └── Scripts/
│       ├── 00_Create_database_or_tables.sql
│       ├── 01_Database_exploration.sql
│       ├── 02_Dimension_exploration.sql
│       ├── 03_Data_range_exploration.sql
│       ├── 04_Measures_exploration.sql
│       ├── 05_Magnitude_analysis.sql
│       ├── 06_Ranking_analysis.sql
│       ├── 07_Change_over_time_analysis.sql
│       ├── 08_Cumulative_analysis.sql
│       ├── 09_Performance_analysis.sql
│       ├── 10_Data_segmentation.sql
│       ├── 11_Part_to_whole_analysis.sql
│       ├── 12_Report_customer.sql
│       └── 13_Report_product.sql


---

## ⚙️ ETL Workflow

1. Extract → Load raw data into Bronze tables  
2. Transform → Clean & standardize data in Silver layer  
3. Load → Create Gold layer analytical tables  

---

## 📈 Analysis Performed

- Data exploration
- Ranking analysis
- Change-over-time analysis
- Cumulative analysis
- Performance analysis
- Data segmentation
- Part-to-whole analysis

---

## 🧠 SQL Skills Used

- Joins
- CTE (Common Table Expressions)
- Window Functions
- Aggregations
- CASE statements
- Ranking functions
- Star Schema modelling

---

## 🎯 Outcome
Built a complete SQL-based analytics pipeline using modern data warehouse practices for business reporting.

---

## 🚀 Repository Description
End-to-end SQL Data Analysis project implementing ETL process and modern data warehouse architecture (Bronze, Silver, Gold layers).
