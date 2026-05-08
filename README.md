# SQL Data Warehouse Project

This project focuses on building a comprehensive data warehouse using **SQL Server (T-SQL)**. It covers the entire data lifecycle, including **ETL processes**, **Data Modeling**, and **Business Analytics** using modern engineering standards.

---

##  Data Architecture

The project follows the **Medallion Architecture**, which organizes data into three distinct layers to ensure quality, reliability, and performance.

###  Bronze Layer (Raw Data)
* **Goal:** Acts as a landing zone for data in its original form.
* **Process:** Raw data is ingested directly from CSV files into SQL Server without modification.
* **Integrity:** Preserves the "source of truth" for future reprocessing.

###  Silver Layer (Cleaned Data)
* **Goal:** Provides a refined, consistent view of the data.
* **Process:** * Cleans and transforms raw data to handle missing values and nulls.
    * Resolves data inconsistencies and formatting issues.
    * Implements standardization and normalization for better performance.

###  Gold Layer (Business Layer)
* **Goal:** Powers reporting and high-level decision-making.
* **Structure:** Implements a **Star Schema** consisting of Fact and Dimension tables.
* **Optimization:** Designed specifically for fast analytical queries and BI dashboarding.

---

##  Visualizations & Schemas

### 1. Medallion Pipeline Flow
![Architecture Diagram](https://github.com/samyak-10/sql-data_warehouse-project/blob/main/docs/DWH_ARCHITECHURE%20.jpg?raw=true)

### 2. Star Schema (ERD)
![ERD Diagram](https://github.com/samyak-10/sql-data_warehouse-project/blob/main/docs/DWH_STAR_SCHEMA.drawio.png?raw=true)

---

##  Project Objectives

### Data Warehouse Engineering
* **Integration:** Seamlessly combine **ERP** and **CRM** datasets into a unified SQL environment.
* **Transformation:** Apply complex business logic during the ETL phase to clean raw data.
* **Modeling:** Establish a robust analytical model (Star Schema) that serves as the foundation for the warehouse.

### Analytics & Data Analysis
The final layer generates insights regarding:
* **Customer Behavior:** Tracking engagement and purchasing patterns.
* **Product Performance:** Identifying top-selling items and inventory efficiency.
* **Sales Trends:** Visualizing growth and seasonal fluctuations.

---

##  Project Overview

1. **Architecture Design:** Modern Data Warehouse implementation using the Medallion framework.
2. **ETL Pipelines:** Robust Extract, Transform, and Load workflows built with T-SQL.
3. **Data Modeling:** Creation of Fact and Dimension tables for optimized storage and retrieval.
4. **Analytics:** SQL-based reporting to provide actionable business insights.
