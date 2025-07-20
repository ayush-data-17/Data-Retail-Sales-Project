# Data-Retail-Sales-Project

# 🧹 Retail Store Data Cleaning (Excel-Based)

<p
Before Cleaning The Retail Data= 
After Cleaning The Retail Data= 
Screenshot of Before Cleaning The Retail Data= 
Screenshot of After Cleaning The Retail Data= 

## 🛍️ Project Overview

This project involved cleaning and preparing **retail transaction data** using **Microsoft Excel**. The dataset contained various inconsistencies and formatting issues that were resolved through manual data cleaning techniques.

The cleaned data is now ready for **reporting, dashboarding, or import into BI tools** like Power BI or Tableau.

---

## 📦 Dataset Description

The dataset includes the following columns:

| Column Name       | Description                                          |
|-------------------|------------------------------------------------------|
| `Category`        | Product category/type                                |
| `Transactions`    | Unique transaction ID                                |
| `Per Unit`        | Price per unit of the item                           |
| `Items`           | Item name or description                             |
| `Quantity`        | Number of items purchased                            |
| `Location`        | Store location or region                             |
| `PaymentMethod`   | Mode of payment (e.g., Cash, Card, Online)           |
| `Transaction Date`| Date of transaction (usually includes time as well)  |

---

## 🧼 Cleaning Steps Performed (in Excel)

| Cleaning Task                        | Excel Feature/Tool Used               |
|--------------------------------------|---------------------------------------|
| Removed duplicate transactions       | `Remove Duplicates` tool              |
| Handled missing values               | Filters + manual review               |
| Standardized date format             | Format Cells → Date (YYYY-MM-DD)      |
| Cleaned text fields (`Items`, etc.)  | `TRIM()`, `PROPER()`, `CLEAN()`       |
| Corrected inconsistent categories    | `Data Validation` + dropdown lists    |
| Fixed numerical data types           | Formatted `Per Unit` and `Quantity`   |
| Removed invalid quantities or prices | Conditional Formatting + Filtering    |
| Sorted data by date and location     | Sort by `Transaction Date`            |
| Verified `PaymentMethod` consistency | `COUNTIF()` + Data Validation         |
| Final save to new cleaned file       | Saved as `cleaned_retail_data.xlsx`   |

---

## 📁 Folder Structure

