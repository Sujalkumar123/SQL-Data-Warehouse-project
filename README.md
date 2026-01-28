# SQL-Data-Warehouse-project

Welcome to the **Data Warehouse and Analytics Project** repository 🚀  
This project demonstrates an end-to-end **data warehousing and analytics solution**, from raw data ingestion to generating actionable business insights.

Designed as a **portfolio project**, it follows **industry best practices** in data engineering, data modeling, and analytics.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** consisting of three layers:

### 🔹 Bronze Layer
- Stores raw data exactly as received from source systems  
- Data is ingested from **CSV files** into **SQL Server**

### 🔹 Silver Layer
- Performs data cleansing, standardization, and normalization  
- Prepares high-quality data for analytical use

### 🔹 Gold Layer
- Contains business-ready data  
- Modeled using a **star schema** for reporting and analytics

---

## 📖 Project Overview

This project includes:

- **Data Architecture**: Designing a modern data warehouse using the Medallion approach  
- **ETL Pipelines**: Extracting, transforming, and loading data into SQL Server  
- **Data Modeling**: Creating fact and dimension tables optimized for analytics  
- **Analytics & Reporting**: Writing SQL queries to generate meaningful insights  

---

## 🎯 Who Is This Project For?

This repository is ideal for showcasing skills in:

- SQL Development  
- Data Engineering  
- Data Architecture  
- ETL Pipeline Development  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Tools & Resources (All Free)

- **Datasets** – ERP & CRM CSV files  
- **SQL Server Express** – Database engine  
- **SQL Server Management Studio (SSMS)** – Database management GUI  
- **GitHub** – Version control and collaboration  
- **Draw.io** – Architecture, data flow, and modeling diagrams  
- **Notion** – Project templates and structured steps  

---

## 🚀 Project Requirements

### 🔹 Building the Data Warehouse (Data Engineering)

**Objective**  
Build a modern SQL Server data warehouse to consolidate sales data and support analytical reporting.

**Specifications**
- **Data Sources**: ERP and CRM systems (CSV files)  
- **Data Quality**: Clean and resolve data issues before analysis  
- **Integration**: Combine multiple sources into a unified analytical model  
- **Scope**: Latest data only (no historization required)  
- **Documentation**: Clear documentation for business and analytics teams  

---

### 🔹 BI, Analytics & Reporting (Data Analysis)

**Objective**  
Develop SQL-based analytics to generate insights into:

- Customer Behavior  
- Product Performance  
- Sales Trends  

These insights help stakeholders make data-driven business decisions.

📄 For full details, see: `docs/requirements.md`

---

## 📂 Repository Structure

data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
