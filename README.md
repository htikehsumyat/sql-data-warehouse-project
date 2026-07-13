# Data Warehouse and Analytics Project
This repository showcases my implementation of an **end-to-end data warehouse** built with **SQL Server**. It demonstrates the complete data warehousing process, from data ingestion and ETL pipelines to dimensional data modeling and SQL-based analytics.

## 🏗️ Data Architecture
The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

1. **Bronze Layer**: Stores raw data ingested directly from source systems without transformations. Data is loaded from CSV files into SQL Server while preserving the original structure.
2. **Silver Layer**: Applies data cleansing, standardization, and transformation processes to improve data quality and prepare the data for analytical use.
3. **Gold Layer**: Contains curated, analytics-ready data modeled using a star schema, optimized for reporting and analytical queries.

## 📖 Project Overview
This project demonstrates:

1. **Data Architecture**: Building a modern data warehouse using the **Bronze**, **Silver**, and **Gold** layers of the Medallion Architecture.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Creating fact and dimension tables optimized for analytics.
4. **Analytics & Reporting**: Writing SQL queries to analyze and extract meaningful insights from the data.

## 🎯 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

## 🌟 Acknowledgement
This project was completed as part of the **SQL Course** by **Data with Baraa**. The project concept and learning materials are based on the course, while the implementation in this repository reflects my own hands-on work completed for learning and portfolio development.
