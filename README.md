# 🛒 Retail Sales ETL Pipeline

An end-to-end **ETL (Extract, Transform, Load)** project built with **Python, Pandas, SQLite, and SQL** to demonstrate the fundamentals of a Data Engineering workflow.

---

## 📌 Overview

This project extracts retail sales data from a CSV file, cleans and transforms it using Pandas, loads it into a SQLite database, performs business analysis with SQL, and generates a sales report.

This project was built to practice core Data Engineering concepts including:

- Data Extraction
- Data Cleaning
- Data Transformation
- Database Loading
- SQL Analysis
- Report Generation

---

## 🛠️ Tech Stack

- 🐍 Python
- 🐼 Pandas
- 🗄️ SQLite
- 📊 SQL
- 📓 Jupyter Notebook
- 📝 Git & GitHub

---

## 📂 Project Structure

```text
Retail-Sales-ETL/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── database/
│   └── retail.db
│
├── reports/
│   └── report.txt
│
├── screenshots/
│   ├── raw-data.png
│   ├── cleaned-data.png
│   ├── sql-output.png
│   └── report.png
│
├── sql/
│   └── queries.sql
│
├── main.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

---

# 🔄 ETL Workflow

```text
Raw CSV
   │
   ▼
Extract
   │
   ▼
Clean & Transform
   │
   ▼
Load into SQLite
   │
   ▼
SQL Analysis
   │
   ▼
Generate Report
```

---

# ✨ Features

- Read raw CSV dataset
- Handle missing values
- Remove duplicate records
- Create new calculated columns
- Store cleaned data in SQLite
- Execute SQL queries
- Generate business insights
- Export summary report

---

# 📊 Business Analysis

The project performs the following analyses:

- Total Revenue
- Total Orders
- Average Order Value
- Revenue by City
- Revenue by Category
- Top Selling Product
- Top Customer
- Monthly Revenue

---

# 📈 Learning Outcomes

Through this project I learned how to:

- Build an end-to-end ETL pipeline
- Clean and transform datasets using Pandas
- Store data in SQLite databases
- Write SQL queries for business analysis
- Generate reports from processed data
- Organize a Data Engineering project using a clean folder structure

---

# 📸 Project Preview

## 📄 Raw Dataset

![Raw Dataset](screenshots/raw-data.png)

---

## 🧹 Cleaned Dataset

![Cleaned Dataset](screenshots/cleaned-data.png)

---

## 🗄️ SQL Query Output

![SQL Output](screenshots/sql-output.png)

---

## 📑 Generated Report

![Report](screenshots/report.png)

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/pratimaasapkota/retail-sales-etl-pipeline.git
```

Move into the project folder:

```bash
cd retail-sales-etl-pipeline
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open **main.ipynb** and run all cells.

---

# 🚀 Future Improvements

- PostgreSQL Integration
- Apache Airflow
- Docker
- Streamlit Dashboard
- Power BI Dashboard
- Automated Scheduling
- Cloud Deployment (AWS/GCP)

---

# 👩‍💻 Author

**Pratima Sapkota**

Computer Engineering Student | Aspiring Data Engineer

GitHub: https://github.com/pratimaasapkota

## 🛠️ Built With

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![SQLite](https://img.shields.io/badge/SQLite-Database-blue?logo=sqlite)
![SQL](https://img.shields.io/badge/SQL-Queries-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-yellow)


---

## ⭐ If you found this project useful, consider giving it a star!