
# 📊 Data Warehouse & Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀
This portfolio project showcases a full-stack data warehousing and analytics solution—demonstrating best practices in **data engineering**, **ETL development**, and **business intelligence**.

---

## 🏗️ Data Architecture

The solution follows the **Medallion Architecture** consisting of three distinct layers:

* **Bronze Layer:**
  Raw data ingestion from source systems (CSV files) into a SQL Server database—preserving original datasets.

* **Silver Layer:**
  Cleansed, standardized, and normalized data—ready for structured processing and business logic.

* **Gold Layer:**
  Business-ready data modeled using **Star Schema** to support reporting, dashboarding, and deep analytical queries.

---

## 📖 Project Overview

This project covers:

* **Data Architecture:**
  End-to-end design using the Medallion pattern—Bronze, Silver, and Gold layers.

* **ETL Pipelines:**
  Extracting, transforming, and loading data using SQL Server scripts across all layers.

* **Data Modeling:**
  Creation of Fact and Dimension tables for efficient querying and analysis.

* **Analytics & Reporting:**
  SQL-based analysis to drive insights into sales performance, customer behavior, and product trends.

---

## 🎯 Who Is This For?

This repository is ideal for professionals and students aiming to showcase skills in:

* SQL Development
* Data Architecture
* Data Engineering
* ETL Pipeline Development
* Data Modeling
* Business Analytics

---

## 🛠️ Tools & Resources

Everything you need to complete and run this project is **free and open-source**:

| Tool                                       | Purpose                              |
| ------------------------------------------ | ------------------------------------ |
| 📁 **CSV Datasets**                        | Provided ERP and CRM data files      |
| 🗃️ **SQL Server Express**                 | Lightweight database engine          |
| 🧰 **SQL Server Management Studio (SSMS)** | GUI for managing SQL Server          |

---

## 🚀 Project Requirements

### 🔹 Phase 1: Data Engineering – Build the Data Warehouse

**Objective:**
Design a modern data warehouse in SQL Server to centralize and prepare sales data for analysis.

**Key Specifications:**

* **Data Sources:** CSV files from ERP and CRM systems
* **Data Quality:** Clean and standardize datasets
* **Integration:** Create a unified, analytics-optimized model
* **Scope:** Focus on the latest data only (no historization)
* **Documentation:** Include metadata and data model descriptions

---

### 🔸 Phase 2: Data Analysis – BI & Reporting

**Objective:**
Generate SQL-based insights to support business decision-making.

**Focus Areas:**

* Customer Segmentation & Behavior
* Product Performance Analysis
* Sales Trend Visualization

📄 *Refer to `docs/requirements.md` for complete functional and technical details.*

---

## 📬 Get Started

1. Clone the repository
2. Install SQL Server & SSMS
3. Load datasets using `scripts/bronze`
4. Transform using `silver` and `gold` layers
5. Start exploring data via SQL or connect Power BI/Tableau for dashboards

---

## 📘 License

This project is open-source under the [MIT License](./LICENSE).


