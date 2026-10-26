# Retail Sales Exploratory Data Analysis

**Track:** Data Analytics — Level 1, Task 1  
**Author:** Abinaya

## Objective
Explore retail transaction patterns, customer demographics, and category sales; document data quality and provide cautious, data-based recommendations.

## Files
- Retail_Sales_EDA.ipynb — full analysis notebook with charts, findings, and recommendations.
- retail_sales_dataset.csv — the source dataset used by the notebook.

## Dataset
Source: [Retail Sales Dataset on Kaggle](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset). The dataset page describes the data as synthetic practice data and lists a CC0 public-domain license. It contains 1,000 transaction rows and nine columns.

## Run the notebook
1. Open the notebook with Google Colab or Jupyter.
2. Keep the CSV in the same folder as the notebook, or upload it when the notebook prompts you.
3. Run the cells from top to bottom. The notebook creates charts and displays analysis tables.

## Main findings
- The dataset has no missing values or duplicate rows; all 1,000 transaction totals equal quantity multiplied by price per unit.
- May has the highest 2023 monthly revenue (53,150); September has the lowest (23,620).
- Q4 2023 has the highest quarterly revenue (126,190); Q3 has the lowest (96,045).
- Clothing leads unit volume (894 units); Electronics has the highest revenue (156,905).
- Average spend is nearly identical for female (456.55) and male (455.43) transactions.
- The source has product categories but no individual product name or SKU, so it cannot support a top-10 individual-product ranking.

## Limitations
This is synthetic data covering one year, with two transactions on January 1, 2024. Trend comparisons use complete 2023 months and quarters. Each customer ID appears once, so the data cannot measure repeat purchases or lifetime value. Treat findings as practice insights, not business facts.
