# SQL Data Warehouse & Analytics Project

## 📌 Project Overview

This project demonstrates the design and implementation of a modern SQL Server data warehouse using CRM and ERP source data.

The project follows a Bronze–Silver–Gold layered architecture to ingest raw data, perform data cleaning and transformation, integrate multiple source systems, and create business-ready analytical views using a Star Schema.

The warehouse is designed to provide a reliable and structured foundation for SQL-based data analysis and business intelligence reporting.

---

## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:

![Data Architecture](docs/data_architecture.png)

1. Bronze Layer: Stores raw data as it is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications

- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analytics)

#### Objective

Develop SQL-based analytics to deliver detailed insights into:

- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

---

## 🌟 About Me

Hi there! I'm **G Bala Sahas Reddy**, I'm a B.Tech Computer Science & Engineering graduate building my skills in **SQL, Data Analytics, Power BI, Excel, and Python**.

I enjoy working with data, solving analytical problems, and building practical projects to develop my skills.
