## 📌 PAN Card Data Cleaning & Validation Project
This project focuses on cleaning and validating Indian PAN (Permanent Account Number) data using SQL (PostgreSQL) and Python.
It simulates a real-world data engineering/data analyst task, where raw data is messy and needs to be transformed into clean, reliable data for analysis.

## 🚀 Project Objectives
- Clean messy PAN data
- Validate PAN format using regex
- Handle missing and invalid values
- Remove duplicate records
- Detect patterns like:
 - Adjacent repeating characters
 - Sequential patterns
- Build a summary report of valid vs invalid PANs

## 🛠️ Tech Stack
- SQL (PostgreSQL)
- Python
- Regex (Regular Expressions)
- Pandas (for Python implementation)

## 🧹 Data Cleaning Steps
- Trim spaces and convert to uppercase
- Remove null/blank values
- Remove duplicates
- Identify invalid formats
- Flag suspicious patterns

## 📊 Key Features
## ✅ SQL Implementation
- Regex-based validation
- Custom functions (PL/pgSQL)
- Duplicate removal
- Summary reporting

## ✅ Python Implementation
- Modular reusable functions
- Regex validation
- Pandas-based cleaning
- Easy-to-extend pipeline

## 📈 Output / Results
- Total records processed
- Valid PAN count
- Invalid PAN count
- Duplicate records removed
- Pattern-based anomaly detection


## 💡 Use Cases
- Data cleaning pipelines
- KYC validation systems
- Financial data preprocessing
- Interview portfolio project

## 🧠 What I Learned
- Writing production-level SQL queries
- Using regex for real-world validation
- Data quality checks in pipelines
- Structuring reusable Python code

## 🔗 Future Improvements
- Add Streamlit dashboard
- Automate pipeline using Airflow
- Deploy as API using FastAPI
