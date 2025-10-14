# 🏢 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a complete **end-to-end data warehousing and analytics pipeline**, from ingesting raw data to generating business-ready insights.  

It is designed as a **portfolio-grade project** to showcase practical skills in **Data Engineering**, **ETL Development**, and **Data Analytics**, following modern industry standards.

---

## 🏗️ Data Architecture — Medallion Framework

This project implements the **Medallion Architecture**, which structures data into three progressive layers for clarity, scalability, and performance.

### Data Architecture

1. **🟤 Bronze Layer (Raw Layer)**  
   - Stores raw data directly from source systems (ERP & CRM).  
   - Data is imported from CSV files into **SQL Server** without modifications.

2. **⚪ Silver Layer (Refined Layer)**  
   - Performs data **cleaning, standardization, deduplication**, and **transformation**.  
   - Ensures data consistency and accuracy for analysis.

3. **🟡 Gold Layer (Analytics Layer)**  
   - Contains **business-ready data** structured in a **star schema**.  
   - Supports analytical queries, dashboards, and reporting.

---

## 📖 Project Overview

This project highlights how to build and manage a modern data warehouse using SQL Server and SQL-based ETL techniques.

### Core Components
1. **Data Architecture** – Designing the warehouse with Bronze, Silver, and Gold layers.  
2. **ETL Pipelines** – Extracting, transforming, and loading data from source systems.  
3. **Data Modeling** – Creating star schema models (fact and dimension tables).  
4. **Analytics & Reporting** – Generating SQL-based reports and insights.

🎯 This project demonstrates strong understanding and hands-on experience with:
- Data Engineering Workflows  
- SQL Development  
- ETL and Data Pipelines  
- Data Modeling (Star Schema)  
- Business Intelligence & Analytics  

---

## 🛠️ Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| Database | **SQL Server Express** |
| IDE | **SQL Server Management Studio (SSMS)** |
| Data Visualization | Power BI / SQL Queries |
| Design & Documentation | **DrawIO**, **Notion**, **Markdown** |
| Version Control | **Git & GitHub** |

**All tools used are free and beginner-friendly.**

---

## 🚀 Project Requirements

### 🧱 Data Engineering Phase — Building the Data Warehouse

**Objective:**  
Design and develop a **data warehouse** that consolidates ERP and CRM data, cleanses inconsistencies, and prepares it for business analytics.

**Specifications:**
- Import datasets from **ERP** and **CRM** systems (CSV files).  
- Clean and standardize data in the **Silver Layer**.  
- Create **analytical models** in the **Gold Layer** for reporting.  
- Provide documentation for easy understanding of data structures.  
- Focus on the **latest dataset** (no historization required).  

---

### 📊 Analytics & Reporting Phase — Business Intelligence

**Objective:**  
Deliver analytical insights through SQL-based reporting to answer key business questions on:

- Customer behavior  
- Product performance  
- Sales performance & trends  

**Outcome:**  
Empower stakeholders with **data-driven insights** and **actionable KPIs**.

More detailed requirements and analytical queries can be found in:  
📄 [`docs/requirements.md`](docs/requirements.md)

---

## 📂 Repository Structure

```
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
```

---

## 📈 Key Learnings

Through this project, you will:
- Understand the **Medallion Data Architecture**.
- Learn how to design **ETL workflows** in SQL.
- Apply **data cleaning and transformation** techniques.
- Build a **star schema** optimized for analytics.
- Derive **business insights** using SQL queries.

---

## 🧠 Future Improvements

- Automate ETL pipelines using **Python / Airflow**.  
- Implement incremental loads for real-time updates.  
- Integrate **Power BI dashboards** for visual analytics.  
- Migrate to cloud platforms like **Azure Synapse** or **AWS Redshift**.

---

## 🛡️ License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and share with proper credit.

---

## 🙋‍♂️ About the Author

Hi! I’m **Sanjay Mudela**, an aspiring **Data Engineer** passionate about building scalable data systems and transforming raw data into business value.

I created this project to deepen my understanding of **Data Warehousing** and **Analytics**, and to help others learn practical, real-world data engineering concepts.

Let’s connect and grow together! 🌐  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sanjay-mudela)  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SanjayMudela)
