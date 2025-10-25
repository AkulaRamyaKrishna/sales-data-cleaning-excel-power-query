# Sales Data Cleaning and Transformation using Excel Power Query

### 📋 Project Overview
This project focuses on cleaning and transforming raw sales data using **Excel Power Query**.  
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
  - **Profit Margin (%)** = `(Profit / Revenue) × 100`
- Ensured consistent rounding and formatting for numeric fields  

### 🗂️ Files Included
- `Sales_Data - Cleaned_file.xlsx` → cleaned and transformed dataset (exported from Power Query)  
- `Documentation - excel_power Query_PDF` → step-by-step explanation with screenshots of cleaning and transformation process  

### 🧰 Tools Used
- Microsoft Excel  
- Power Query Editor  

### 🎯 Outcome
A cleaned and transformed sales dataset with added business metrics, ready for further analysis or visualization in Excel or Power BI.
