# Task 2 — Customer Segmentation Analysis

## Track
Data Analytics (Level 1/2)

## Objective
Apply clustering algorithms to segment an e-commerce company's customer base into distinct
groups based on purchasing behaviour, enabling targeted marketing strategies.

## Dataset
Online Retail Dataset — sourced from Kaggle / UCI Machine Learning Repository.
Contains transaction-level e-commerce data: InvoiceNo, StockCode, Description, Quantity,
InvoiceDate, UnitPrice, CustomerID, Country.

## Tech Stack
Python, pandas, scikit-learn (KMeans, StandardScaler), matplotlib, seaborn, Jupyter Notebook

## Key Steps Performed
- Data cleaning: removed rows with missing CustomerID, cancelled orders, and invalid
  quantity/price values
- Descriptive statistics: average purchase value, purchase frequency, customer lifetime value
- RFM feature engineering: Recency, Frequency, Monetary value per customer
- Feature standardisation using StandardScaler
- K-Means clustering with the Elbow Method to determine optimal K
- Cluster visualisation via scatter plots (Recency vs Monetary, Frequency vs Monetary)
- Cluster profiling: mean RFM values and customer type description per cluster
- Bar chart of customer distribution across clusters
- Marketing recommendations tailored to each customer segment

## Key Insights
*(fill in once you've run the notebook, e.g.:)*
- Identified [K] distinct customer segments based on RFM behaviour
- [X]% of customers fall into the "at-risk" segment (high recency, low frequency)
- A small "VIP" segment contributes disproportionately to total revenue

## Files in this Folder
- `Customer_Segmentation_RFM_KMeans.ipynb` — full notebook with code, charts, and analysis
- `screenshots/` — output visualizations
- `README.md` — this file

## Author
[Ananya R Naik]
