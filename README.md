# Nigerian E-commerce Data Cleaning

This repository contains a **messy Nigerian e-commerce sales dataset** and a **Python data cleaning pipeline**. It demonstrates real-world data cleaning challenges and prepares the data for analysis and visualization.

## Dataset

- `raw_sales_data_1000_rows.csv` – Messy 1000-row dataset simulating common inconsistencies:
  - Customer names with inconsistent formatting
  - Phone numbers in multiple formats
  - States with mixed capitalization
  - Products with varied naming
  - Prices with commas and inconsistent formats
  - Multiple date formats
  - Payment status inconsistencies
  - Missing emails and quantities
  - Duplicate orders

## Cleaning Pipeline

- `clean_data.py` / `main.ipynb` – Python scripts that:
  - Standardize text columns (names, states, products, payment status, emails)
  - Clean phone numbers
  - Convert numeric and date columns
  - Handle missing values
  - Remove duplicates

