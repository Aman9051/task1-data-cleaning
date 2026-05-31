# Task 1 - Data Cleaning and Preprocessing

## Objective
Clean and prepare a raw dataset by handling missing values, duplicates, and inconsistent formats.

## Dataset
Mall Customer Segmentation - Kaggle

## Steps Performed
- Renamed columns to lowercase with underscores
- Handled missing values (median for numeric, mode for categorical)
- Removed duplicate rows
- Standardized text values (title case)
- Fixed data types
- Capped outliers using IQR method

## Tools Used
Python, Pandas, NumPy, Jupyter Notebook

## Output
`Mall_Customers_Cleaned.csv` — cleaned and ready for analysis