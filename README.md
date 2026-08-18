# cafe-sales-cleaning-reporting
Automated cafe sales data cleaning, analysis, and reporting using Python and Pandas.
# ☕ Cafe Sales Data Cleaning & Reporting Automation

## 📌 Project Overview

This project demonstrates a data cleaning and reporting workflow using Python and Pandas.

The project uses a dirty cafe sales dataset containing missing values, invalid values, duplicate records, and inconsistent data. The data is cleaned, analyzed, and used to generate an automated sales report and visual summaries.

## 🎯 Objective

The main objectives of this project are to:

- Clean and preprocess raw sales data
- Handle missing and invalid values
- Remove duplicate records
- Correct data types and inconsistent data
- Analyze sales performance
- Generate visual summaries
- Automate the generation of a sales report

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel

## 📂 Dataset

The project uses the **Dirty Cafe Sales Dataset**, containing 10,000 cafe sales transactions.

The raw dataset contains several data-quality issues, including:

- Missing values
- `ERROR` and `UNKNOWN` values
- Duplicate records
- Inconsistent data
- Missing transaction dates

The original dataset is included in this repository as:

`dirty_cafe_sales.csv`

## 🧹 Data Cleaning

The following steps were performed:

1. Loaded and explored the raw dataset
2. Checked missing values
3. Checked duplicate records
4. Identified invalid values
5. Replaced `ERROR` and `UNKNOWN` values with missing values
6. Converted numerical columns to appropriate data types
7. Converted the transaction date column to datetime format
8. Removed the duplicate/misspelled date column
9. Handled missing values
10. Removed records with missing transaction dates
11. Verified the cleaned dataset

After cleaning, the dataset contained **9,540 valid transactions** with no remaining missing values.

## 📊 Sales Analysis

The project analyzes sales using:

- Sales by Item
- Sales by Payment Method
- Sales by Location
- Monthly Sales Trend
- Total Sales
- Total Transactions
- Average Transaction Value
- Top Selling Item

## 🤖 Reporting Automation

The project automates the creation of a sales report from the cleaned dataset.

The automated report calculates important business metrics such as:

- Total Sales
- Total Transactions
- Average Transaction Value
- Top Selling Item

The workflow can be rerun when the source dataset is updated, allowing the cleaned data and report to be regenerated.

## 📸 Automated Report Output

![Automated Cafe Sales Report](Automated%20Cafe%20Sales%20Report.png)

The image above shows an example of the generated automated report.

## 📁 Repository Contents

| File | Description |
|---|---|
| `Cafe_Sales_Cleaning_Reporting.ipynb` | Complete Jupyter Notebook containing data cleaning, analysis, visualization, and reporting |
| `dirty_cafe_sales.csv` | Original raw cafe sales dataset |
| `Cleaned_Cafe_Sales.xls` | Cleaned cafe sales dataset |
| `Automated_Cafe_Sales_Report.xls` | Automated cafe sales report |
| `Automated Cafe Sales Report.png` | Screenshot of the automated report output |
| `README.md` | Project documentation |

## 💡 Key Outcome

This project demonstrates how Python can be used to automate repetitive data preparation and reporting tasks.

Instead of manually cleaning the dataset and calculating business metrics each time, the workflow can be rerun on updated data to generate an updated cleaned dataset and sales report.

## 🚀 Conclusion

This project provides practical experience in **data cleaning, preprocessing, exploratory data analysis, visualization, automation, and business reporting** using Python.
