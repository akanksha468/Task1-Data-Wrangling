# Task 1: Data Immersion & Wrangling

## Objective
The objective of this task is to understand the dataset and perform data cleaning and transformation to prepare it for analysis.

---

## Dataset Description
The dataset contains sales transaction details including product information, quantity, price, customer ID, and country.

---

## Data Dictionary

| Column Name | Data Type | Description | Business Relevance |
|------------|-----------|-------------|-------------------|
| InvoiceNo | object | Unique order number | Helps track each transaction |
| StockCode | object | Product code | Identifies product |
| Description | object | Product name | Product details |
| Quantity | int | Number of items purchased | Sales volume |
| InvoiceDate | datetime | Date of purchase | Time-based analysis |
| UnitPrice | float | Price per product | Revenue calculation |
| CustomerID | float | Unique customer ID | Customer tracking |
| Country | object | Customer location | Geographic analysis |
| TotalSales | float | Quantity × UnitPrice | Total revenue |

---

## Data Cleaning Steps

1. Imported dataset using Pandas
2. Checked dataset structure using info() and shape
3. Identified missing values using isnull()
4. Removed duplicate rows
5. Converted InvoiceDate column to datetime format
6. Created new column TotalSales = Quantity × UnitPrice
7. Removed invalid values (negative Quantity and UnitPrice)
8. Saved cleaned dataset as cleaned_data.csv

---

## Tools Used

- Python
- Pandas
- Jupyter Notebook / VS Code

---

## Files in Repository

- Task1.ipynb → Python code for data cleaning
- data.csv → original dataset
- cleaned_data.csv → cleaned dataset
- README.md → project documentation

---

## Conclusion

The dataset was successfully cleaned and transformed into an analysis-ready format. This dataset can now be used for Exploratory Data Analysis (EDA) and visualization.
