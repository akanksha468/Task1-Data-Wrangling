# Task 1: Data Immersion & Wrangling

## Objective
The objective of this task is to understand the dataset and perform data cleaning and preprocessing so that the data becomes ready for analysis.

## Dataset Information
The dataset contains e-commerce sales transaction details including product information, customer details, quantity purchased, price, and purchase date.

## Columns Description (Data Dictionary)

| Column Name | Description |
|------------|------------|
| InvoiceNo | Unique invoice number for each transaction |
| StockCode | Unique product code |
| Description | Name of the product |
| Quantity | Number of items purchased |
| InvoiceDate | Date and time of purchase |
| UnitPrice | Price per item |
| CustomerID | Unique ID of customer |
| Country | Country of customer |
| TotalSales | Total sales value (Quantity × UnitPrice) |
| Year | Year extracted from InvoiceDate |
| Month | Month extracted from InvoiceDate |
| Day | Day extracted from InvoiceDate |

## Steps Performed

### 1. Data Loading
Loaded dataset using Pandas.

### 2. Data Understanding
Checked:
- shape of dataset
- column names
- data types
- statistical summary

### 3. Data Cleaning
- handled missing values
- removed duplicate rows
- removed negative quantity values
- removed zero price values

### 4. Data Transformation
- converted InvoiceDate column to datetime format
- created new column TotalSales
- extracted Year, Month and Day from InvoiceDate

### 5. Final Output
Generated cleaned dataset ready for analysis.

## Files in Repository

- Task1.ipynb → Python notebook with cleaning code
- cleaned_data.csv → cleaned dataset
- README.md → project documentation

## Tools Used
- Python
- Pandas
- NumPy
- VS Code

## Conclusion
The dataset was successfully cleaned and transformed into analysis-ready format. Missing values, duplicates, and incorrect data were handled, and new useful columns were created for future analysis.
