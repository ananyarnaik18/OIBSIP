# Task 3 — Cleaning Data

## Track
Data Analytics (Level 1/2)

## Objective
Take a deliberately messy dataset and systematically transform it into a clean, analysis-ready
dataset, documenting every decision made along the way.

## Dataset
Titanic Dataset — sourced from Kaggle. A classic messy dataset containing missing values
(Age, Cabin, Embarked), inconsistent formatting, and outliers, commonly used for data cleaning
practice.

## Tech Stack
Python, pandas, numpy, Jupyter Notebook

## Key Steps Performed
- Data quality report: null counts, duplicate rows, dtype overview, numeric value ranges
- Missing data handling with per-column justification (median/mode imputation, column
  dropping with signal preservation, row deletion where appropriate)
- Duplicate row detection and removal (documented count removed)
- Standardisation of inconsistent categorical values and formatting
- Outlier detection using the IQR method, with documented cap/remove/retain decisions per column
- Data type correction (IDs as string, categorical flags as category, monetary values as float)
- Before vs. after summary table (row count, null count, duplicate count, dtype accuracy)
- Cleaned dataset exported to `cleaned_data.csv`

## Key Insights
*(fill in once you've run the notebook, e.g.:)*
- Reduced total null values from [X] to [Y] through targeted, justified imputation
- Removed [N] duplicate rows
- Standardised inconsistent categorical formatting across [column names]
- Capped [N] outlier values in [column] using the IQR method rather than removing rows outright

## Files in this Folder
- `Data_Cleaning_Task3.ipynb` — full notebook with code, data quality report, and documented
  cleaning decisions
- `cleaned_data.csv` — the final cleaned dataset output
- `screenshots/` — output tables and summaries
- `README.md` — this file

## Author
[Ananya R Naik]
