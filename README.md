# cafe-sales-data-cleaning
Data Cleaning &amp; Visualization project on cafe sales dataset using Python (Pandas, Seaborn, Matplotlib).

# Cafe Sales Data Cleaning & Visualization

This project cleans a dirty cafe sales dataset and builds visualizations to understand sales patterns.

## Tech Stack
- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Jupyter Notebook

## Steps Performed
- Loaded raw cafe sales CSV with errors and missing values.
- Cleaned invalid entries (`ERROR`, `UNKNOWN`).
- Converted numeric columns and handled missing values with median.
- Removed duplicates and extreme outliers.
- Created visualizations:
  - Top items sold
  - Sales distribution
  - Payment method share
  - Location-wise average sale
  - Monthly sales trend
  - Item-wise average price

## Files
- `Data_Cleaning_Project.ipynb` – main notebook
- `clean_cafe_sales_final.csv` – cleaned dataset
- `profit_summary.csv` – summary table
- `chart*.png` – generated visualizations
