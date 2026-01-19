# 👨🏻‍💻Customer Behavior Data Analyst Portfolio Project
This project represents a complete, industry standard, end-to-end data analytics workflow, designed to mirror the real responsibilities of professional analysts in modern business environments. The project encompasses all critical stages of data analysis, from data preparation and modeling to insight generation, visualization.

## 📌 Project Overview
The goal of this project is to simulate a corporate-grade end-to-end data analytics workflow, demonstrating the ability to translate raw data into strategic business intelligence by:

* ✅ Data Preparation,Modeling & Exploratory Data Analysis (Python): Clean and transform the raw dataset for analysis.

* ✅ Data Analysis (SQL): Simulate business transactions, and run queries to extract insights on customer segments, loyalty, and purchase drivers.

* ✅ Visualization & Insights (Power BI): Build an interactive dashboard that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.



---

## 🧰 Tools & Technologies Used
- **Python** (Pandas, NumPy, SQLAlchemy)
- **Jupyter Notebook**
- **SQL** (MySQL / PostgreSQL / MS SQL Server)
- **Power BI**

---

## 🧪 Notebook: `customer_data_preprocessing.ipynb`

### 1️⃣ Data Import
- Load customer shopping dataset using Pandas
- Inspect data types and structure

### 2️⃣ Data Exploration
- Summary statistics
- Customer behavior trends
- Missing value analysis

### 3️⃣ Data Cleaning
- Handle missing values
- Remove duplicates
- Standardize column names and formats

### 4️⃣ Database Connection
- Connect Python to SQL Database using SQLAlchemy
- Supports:
  - MySQL
  - PostgreSQL
  - MS SQL Server

### 5️⃣ Load Data into SQL Database
- Create database and tables
- Insert cleaned data from Python into SQL
- Verify successful data load

---

## 🗄️ SQL File: `Customer Shopping Behavior Analysis.sql`

### Business Questions Answered:
- Who are the top spending customers?
- Which product categories generate the most revenue?
- Monthly and yearly sales trends
- Customer purchase frequency analysis
- Average order value by segment

Each query is written with:
- Clear comments
- Optimized joins and aggregations

---

## 📊 Power BI Dashboard: `Customer_Behaviour_dashboard.pbix`

### Features:
- Interactive filters (date, category, customer segment)
- KPIs:
  - Total Revenue
  - Average Order Value
  - Customer Count
- Visuals:
  - Sales trends
  - Category-wise revenue
  - Customer segmentation

### Steps:
1. Connect Power BI to SQL Database
2. Import tables
3. Build relationships
4. Create interactive visuals and slicers

---
