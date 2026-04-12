# 📊 SQL Data Warehouse Project

This project focuses on building a comprehensive data warehouse using **Oracle Database**. It covers the entire data lifecycle, including **ETL processes**, **Data Modeling**, and **Business Analytics**.

---

##  Data Architecture

The project follows the **Medallion Architecture**, which organizes data into three distinct layers to ensure quality and reliability.

###  Bronze Layer (Raw Data)
* **Goal:** Acts as a landing zone for data in its original form.
* **Process:** Raw data is ingested directly from CSV files into SQL Server without modification.
* **Integrity:** Preserves the "source of truth" for future reprocessing.

###  Silver Layer (Cleaned Data)
* **Goal:** Provides a refined, consistent view of the data.
* **Process:** * Cleans and transforms raw data to handle missing values.
    * Resolves data inconsistencies and formatting issues.
    * Implements standardization and normalization for better performance.

###  Gold Layer (Business Layer)
* **Goal:** Powers reporting and high-level decision-making.
* **Structure:** Implements a **Star Schema** consisting of Fact and Dimension tables.
* **Optimization:** Designed specifically for fast analytical queries and BI dashboarding.

---

##  Project Objectives

###  Data Warehouse Engineering
* **Integration:** Seamlessly combine **ERP** and **CRM** datasets into one environment.
* **Transformation:** Apply complex business logic during the ETL phase to clean raw data.
* **Modeling:** Establish a unified analytical model that serves as the foundation for the warehouse.

###  Analytics & Data Analysis
The final layer generates insights regarding:
* **Customer Behavior:** Tracking engagement and purchasing patterns.
* **Product Performance:** Identifying top-selling items and inventory efficiency.
* **Sales Trends:** Visualizing growth and seasonal fluctuations.

---

##  Project Overview

1. **Architecture Design:** Modern Data Warehouse implementation using the Medallion framework.
2. **ETL Pipelines:** Robust Extract, Transform, and Load workflows.
3. **Data Modeling:** Creation of Fact and Dimension tables for optimized storage and retrieval.
4. **Analytics:** SQL-based reporting to provide actionable business insights.
