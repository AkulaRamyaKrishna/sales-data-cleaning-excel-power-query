# Excel Power Query – Data Cleaning & Column Formatting

This project demonstrates how raw sales data (CSV format) was imported into Excel and cleaned using Power Query. The goal was to improve data quality, ensure consistent formatting, and prepare the dataset for analysis.

# Data Source

Input File: sales_data.csv
Imported into Excel using:
Data Tab → Get Data → From Text/CSV


### 📋 Project Overview
The dataset was imported from a CSV file, cleaned to remove inconsistencies, and enhanced by adding calculated business metrics such as **Revenue**, **Profit**, and **Profit Margin**.

### 🧹 Data Cleaning Steps
- Imported raw CSV data into Excel Power Query  
- Removed duplicate and blank rows  
- Replaced null or missing values with suitable defaults  
- Trimmed extra spaces and standardized text values  
- Changed data types for numeric and date columns  

### ➕ Data Transformation Steps
- Added new calculated columns:
  - **Revenue** = `Quantity × Unit Price`
  - **Profit** = `Revenue - Quantity * Cost Price]`
  - **Profit Margin (%)** = `Profit / Revenue`
- Ensured consistent rounding and formatting for numeric fields  

### 🗂️ Files Included
- `sales_data_cleaning_excel_power_query.xlsx` → cleaned and transformed dataset (exported from Power Query)  
- `Excel Power Query_ Documentation-PDF` → step-by-step explanation with screenshots of cleaning and transformation process  

### 🧰 Tools Used
- Microsoft Excel  
- Power Query Editor  

### 🎯 Outcome
A cleaned and transformed sales dataset, ready for further analysis or visualization in Excel or Power BI.
