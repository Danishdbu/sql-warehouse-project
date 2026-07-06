# 🚀 SQL Data Warehouse Project | Medallion Architecture

A complete end-to-end **SQL Data Warehouse** project built using **SQL Server** following the **Medallion Architecture (Bronze, Silver, Gold)**.

This project demonstrates how to design a scalable data warehouse, build ETL pipelines using SQL Stored Procedures, clean and transform raw data, create dimensional models, and prepare business-ready datasets for reporting and analytics.

---

# 📌 Project Overview

The project simulates a real-world Data Engineering workflow where data from multiple source systems is extracted, transformed, and loaded into a centralized SQL Server Data Warehouse.

The implementation follows the **Bronze → Silver → Gold** architecture.

- Raw Data Ingestion
- Data Cleaning
- Data Standardization
- Data Transformation
- Star Schema Modeling
- Business Ready Views
- Reporting Layer

---

# 🏗️ High Level Architecture

![High Level Architecture](docs/data_architecture.png)

---

# 🔄 ETL Workflow

![ETL Methods](docs/ETL.png)

---

# 🏢 Source Systems

The project loads data from multiple source systems:

- CRM
- ERP
- CSV Files

Source files are placed inside folders and loaded into SQL Server.

---

# 🥉 Bronze Layer

Purpose:

Store raw source data without applying any transformations.

### Features

- Raw Tables
- Full Load
- Batch Processing
- Truncate & Insert
- Stored Procedures
- No Data Transformation

This layer preserves the original source data exactly as received.

---

# 🥈 Silver Layer

Purpose:

Transform raw data into clean and standardized datasets.

### Transformations

- Remove Duplicates
- Handle NULL Values
- Data Cleaning
- Data Standardization
- Data Normalization
- Derived Columns
- Data Enrichment
- Data Type Conversion

Stored Procedures are used to perform all transformations.

---

# 🥇 Gold Layer

Purpose:

Create business-ready datasets for analytics and reporting.

### Includes

- Star Schema
- Fact Tables
- Dimension Tables
- Business Views
- Aggregated Data
- Business Logic

This layer is optimized for BI tools and SQL analytics.

---

# ⚙️ ETL Process

The ETL pipeline consists of three stages:

## 1. Extract

- Full Extraction
- Incremental Extraction
- CSV Import
- Database Queries

## 2. Transform

- Data Cleaning
- Standardization
- Data Integration
- Aggregations
- Business Rules
- Derived Columns

## 3. Load

- Full Load
- Incremental Load
- Upsert
- Merge
- Truncate & Insert

---

# 📊 Data Warehouse Layers

```
Source Systems
      │
      ▼
 Bronze Layer
(Raw Data Storage)
      │
      ▼
 Silver Layer
(Clean & Standardized Data)
      │
      ▼
 Gold Layer
(Business Ready Data)
      │
      ▼
Reporting / Analytics
```

---

# 🛠️ Technologies Used

- SQL Server
- T-SQL
- Stored Procedures
- SQL Views
- ETL
- Data Warehouse
- Medallion Architecture
- Star Schema
- Git
- GitHub

---

# 📂 Project Structure

```
SQL-Data-Warehouse
│
├── datasets
│
├── bronze
│   ├── Tables
│   └── Stored Procedures
│
├── silver
│   ├── Tables
│   └── Stored Procedures
│
├── gold
│   ├── Views
│   └── Business Models
│
├── architecture
│   ├── data_architecture.png
│   └── ETL.png
│
└── README.md
```

---

# 🎯 Learning Outcomes

By completing this project, I learned:

- SQL Data Warehouse Design
- ETL Pipeline Development
- SQL Stored Procedures
- Data Cleaning
- Data Standardization
- Data Modeling
- Star Schema
- Business Views
- Data Integration
- SQL Best Practices

---

# 🚀 Future Improvements

- Incremental ETL
- Change Data Capture (CDC)
- SQL Agent Automation
- Power BI Dashboard
- Data Quality Validation
- Logging Framework
- Error Handling

---

# 📚 Reference

This project was built for learning purposes by following the excellent Data Engineering tutorial from **Data With Baraa**.

YouTube Tutorial:
https://youtu.be/9GVqKuTVANE

---

# ⭐ If you like this project

Please give this repository a ⭐ on GitHub.

It motivates me to build more Data Engineering and Data Analytics projects.

---

## 👨‍💻 Author

**Mohd Danish**

Aspiring Data Engineer | Data Analyst

- SQL
- Python
- Power BI
- ETL
- Data Warehouse
- Machine Learning

GitHub: https://github.com/your-github

LinkedIn: https://linkedin.com/in/your-linkedin
