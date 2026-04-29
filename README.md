# 📊 SQL Data Warehouse Project

## End-to-End Data Warehousing & Analytics Solution  
**SQL Server | ETL | Data Modelling | Analytics**

This project demonstrates the design and implementation of a modern **data warehouse and analytics solution** using SQL Server. It covers the full data lifecycle from raw data ingestion to transformation, modelling, and analytics reporting following industry-standard data engineering practices.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** framework:
<img width="963" height="601" alt="image" src="https://github.com/user-attachments/assets/c6aeb9ec-2300-49f4-a929-62e955218087" />


### 🥉 Bronze Layer
- Raw data ingested from source CSV files into SQL Server  
- Stores source data in its original format  

### 🥈 Silver Layer
- Data cleansing, standardisation, and transformation  
- Resolves data quality issues and prepares data for modelling  

### 🥇 Gold Layer
- Business-ready analytical layer  
- Data modelled into **fact and dimension tables (Star Schema)** for reporting and analytics  

---

## 📌 Project Objectives

The goal of this project was to build a scalable modern data warehouse to consolidate sales and customer data from multiple source systems and enable analytical reporting.

Key business questions addressed:
- 👥 Customer Behaviour Analysis  
- 📈 Sales Trend Analysis  
- 🛍️ Product Performance Tracking  
- 💡 Business KPI Reporting  

---

## ⚙️ Technical Implementation

### ETL Pipeline Development
- Extracted raw data from ERP and CRM CSV source systems  
- Transformed and cleansed datasets using SQL-based ETL logic  
- Loaded structured data into warehouse layers  

### Data Modelling
- Designed relational warehouse schema using **Star Schema methodology**  
- Created optimised **Fact and Dimension tables** for analytical querying  

### Analytics & Reporting
- Developed SQL-based analytical queries and reports to generate business insights  
- Produced metrics and trend analysis for stakeholders  

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **SQL Server** | Data Warehouse Hosting |
| **SQL Server Management Studio (SSMS)** | Querying & Database Management |
| **Draw.io** | Data Architecture & Schema Design |
| **Git/GitHub** | Version Control & Documentation |

---

## 📊 Skills Demonstrated

- SQL Development  
- ETL Pipeline Design  
- Data Warehousing  
- Data Modelling  
- Star Schema Design  
- Data Cleansing & Transformation  
- Analytical Query Development  
- Business Reporting  

---

## 📈 Business Value Delivered

This solution enables organisations to:
- Consolidate data from multiple source systems  
- Improve data quality and consistency  
- Support data-driven decision-making  
- Generate actionable insights from structured reporting  

---

## 📂 Repository Structure

```bash
SQL-Datawarehouse-Project/
│
├── datasets/                # Source CSV datasets
├── bronze/              # Raw ingestion scripts
├── silver/              # Cleansing/transformation scripts
├── gold/                # Final warehouse models
├── analytics/           # SQL analytical queries/reports
├── docs/                # Architecture diagrams/documentation
└── README.md

Arya Salokhe
📧 aryasalokhe19@gmail.com
