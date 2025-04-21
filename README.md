# Task-1-Elevate-Labs
Excel-based data cleaning and preprocessing task
# 🧹 Data Cleaning and Preprocessing – Excel Task

## 📄 Task Overview

This project involved cleaning and preprocessing a synthetic retail dataset created using the AI tool **Claude**. The dataset simulated real-world data issues commonly encountered in analytics workflows.

## 🧠 Objective

To identify and fix data quality issues such as:
- Missing values and inconsistent formats
- Duplicate records
- Mixed number formatting (e.g., currency symbols)
- Text in numeric fields
- Incorrect total amount calculations
- Inconsistent text capitalization

## 🛠️ Tools Used

- **Microsoft Excel**
- **Claude AI (for dataset generation)**

## 📊 What I Did

- Created a dataset using Claude AI
- Identified issues like null values, inconsistent formatting, and duplicate IDs
- Replaced missing values (`NaN`, blanks) with `"Unknown"`
- Standardized text formats using Excel functions like `PROPER()`
- Removed currency symbols using `SUBSTITUTE()` for calculation accuracy
- Recalculated the `Total_Amount` column using `ARRAYFORMULA`
- Corrected errors and replaced wrong values with computed values
- Sorted data by `Customer_ID` and formatted headers for readability

## 📁 Files Included

- `Original_Dataset.xlsx`: Raw dataset as generated
- `Cleaned_Dataset.xlsx`: Cleaned and final version, ready for analysis
- `README.md`: This file – a brief summary of the project

## ✅ Outcome

A clean, well-structured dataset, free of inconsistencies and ready for further analysis or visualization. All changes were made in Excel using formulas and built-in data cleaning tools.

---


