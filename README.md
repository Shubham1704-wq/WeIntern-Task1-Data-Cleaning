# WeIntern Pvt Ltd – Data Science Week 2 Internship Assignment

## Project Overview
This repository contains the complete solution for the three required tasks:

1. **Task 1 – Data Cleaning Project**
2. **Task 2 – Exploratory Data Analysis**
3. **Task 3 – Sales Prediction Model**

**Dataset chosen:** Sample Superstore Sales (Canadian version, 2009–2012)  
- Raw (messy) version: `raw_superstore_sales.csv`  
- Cleaned version: `cleaned_superstore_sales.csv`

---

## Files Included

| File | Description |
|------|-------------|
| `raw_superstore_sales.csv` | Intentionally messy raw dataset (nulls, duplicates, dirty formats, extra columns) |
| `cleaned_superstore_sales.csv` | Fully cleaned & ready-for-analysis dataset |
| `Task1_Data_Cleaning.ipynb` | Complete data cleaning notebook with documentation |
| `Task2_Exploratory_Data_Analysis.ipynb` | Full EDA with 5+ visualization types + insights |
| `Task3_Sales_Prediction_Model.ipynb` | Full ML pipeline (Linear Regression + Random Forest + tuning) |
| `README.md` | This file |

---

## How to Run

### Option A – Google Colab (Recommended)
1. Upload all files to a Colab folder or Google Drive.
2. Open each `.ipynb` notebook.
3. Update the path if needed (e.g., `/content/cleaned_superstore_sales.csv`).
4. Run all cells in order.

### Option B – Local Jupyter / VS Code
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```
Open the three notebooks and run them sequentially (Task 1 first to generate cleaned data if needed).

---

## Task Summary

### Task 1 – Data Cleaning
- Loaded messy dataset
- Visualized missing data (heatmap)
- Handled nulls (median for numeric, mode for categorical)
- Removed duplicates
- Standardized column names to snake_case
- Fixed dirty string formats in Sales & Quantity
- Converted dates & data types
- Detected outliers (IQR + boxplots) and capped extremes
- Label-encoded key categoricals
- Exported cleaned CSV + comparison report

### Task 2 – EDA
- Descriptive statistics
- Histograms + KDE
- Correlation heatmap
- Box plots by category/region
- Time-series trend (monthly sales & profit)
- Group-by analysis
- Scatter plots
- 3+ actionable business insights + recommendations

### Task 3 – Sales Prediction
- Feature engineering (date parts, shipping delay, category averages)
- 80/20 train-test split
- Linear Regression baseline
- Random Forest Regressor
- Evaluation: RMSE, MAE, R²
- Feature importance plot
- Actual vs Predicted plot + residuals
- Hyperparameter tuning with RandomizedSearchCV
- Business interpretation & limitations

---

## Notes for Review Session
- Be ready to explain why median/mode were chosen for imputation.
- Discuss why Random Forest outperformed Linear Regression.
- Highlight the top features driving sales predictions.
- Mention the discount–profit relationship discovered in EDA.

**Original work – all code is documented and ready for presentation.**

Good luck!
