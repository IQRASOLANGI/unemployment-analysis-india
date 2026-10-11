# Unemployment Analysis in India (COVID-19 Impact)

Exploratory data analysis of unemployment in India, covering regional differences, month-wise trends and the impact of the COVID-19 lockdown.

## Dataset
Kaggle: **Unemployment in India** (`Unemployment in India.csv`). Download it and place it in this folder before running the notebook.

## What the notebook covers
- Data loading, shape inspection, null check and type conversion
- Region-wise average unemployment rate
- Top 10 states with the highest average unemployment rate
- Month-wise all-India trend
- Time series for major states
- Rural vs urban comparison
- Correlation heatmap: unemployment rate, employed, labour participation rate
- Pre-COVID vs post-COVID comparison (split at 25 March 2020), overall and by region

## How to run
```bash
pip install -r requirements.txt
jupyter notebook Unemployment_Analysis.ipynb
```
Then choose **Kernel → Restart & Run All**.

## Tech stack
Python, pandas, NumPy, matplotlib, seaborn, Jupyter Notebook
