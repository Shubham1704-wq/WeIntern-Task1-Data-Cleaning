# Task 1 – Data Cleaning Project
**WeIntern Pvt Ltd | Data Science Week 2 Internship**

## Project Overview
This repository contains the complete **Data Cleaning** solution for the Sample Superstore Sales dataset (Canadian version, 2009–2012).

The raw dataset was intentionally messy (missing values, duplicates, dirty formats, extra columns, inconsistent data types). This notebook transforms it into a clean, analysis-ready dataset.

---

## Files Included

| File | Description |
|------|-------------|
| `Task1_Data_Cleaning.ipynb` | Complete data cleaning notebook with full documentation |
| `raw_superstore_sales.csv` | Original messy raw dataset |
| `cleaned_superstore_sales.csv` | Fully cleaned dataset (ready for EDA & Modeling) |

---

## Cleaning Steps Performed

1. Loaded the raw messy dataset
2. Visualized missing data using heatmap
3. Handled missing values:
   - Median for numeric columns
   - Mode for categorical columns
4. Removed duplicate rows
5. Standardized all column names to `snake_case`
6. Fixed dirty string formats in `Sales` and `Order Quantity`
7. Converted dates and corrected data types
8. Detected outliers using IQR method + Boxplots
9. Capped extreme outliers (Winsorization)
10. Applied Label Encoding on key categorical columns
11. Exported the final cleaned dataset

---

## How to Run

1. Open `Task1_Data_Cleaning.ipynb` in **Google Colab** or **Jupyter Notebook**
2. Make sure `raw_superstore_sales.csv` is in the same folder
3. Run all cells in order

---

## Key Decisions Documented
- Why **median** was preferred over mean for imputation
- Why **mode** was used for categorical columns
- Why outliers were **capped** instead of removed
- Why original categorical columns were retained along with encoded versions

---

**Original work – fully documented and ready for presentation.**
