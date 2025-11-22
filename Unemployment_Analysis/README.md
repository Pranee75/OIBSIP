# Unemployment Analysis in India (2019–2020)

## Project Overview
This project analyzes unemployment trends in India using publicly available datasets. 
It covers data cleaning, exploratory data analysis (EDA), and visualization to extract insights based on regions, areas (Urban vs Rural), and time.

---

## Dataset
Two datasets are used in this project:

1. 'Unemployment in India.csv' – Contains region-wise unemployment data, employment numbers, labor participation, and area type.  
2. 'Unemployment_Rate_upto_11_2020.csv' – Provides unemployment rates with longitude and latitude for regional analysis.

Both datasets were cleaned, missing values handled, and date columns converted for proper analysis.

---

## Libraries & Tools Used
- Python 3  
- Pandas – Data manipulation  
- NumPy – Numerical operations  
- Matplotlib & Seaborn – Data visualization  
- Jupyter Notebook – Interactive coding environment

---

## Project Steps
1. Data Loading – Read CSV files into Pandas DataFrames.  
2. Data Cleaning – Strip column spaces, convert dates, drop irrelevant columns, handle missing data.  
3. Exploratory Data Analysis (EDA) – Checked for null values, duplicates, and basic statistics.  
4. Visualizations:  
    - Unemployment Rate Trend Over Time – Line plot showing how unemployment changed over time.  
    - Average Unemployment Rate by Region – Bar plot comparing regional unemployment rates.  
    - Urban vs Rural Unemployment Rate – Bar plot comparing urban and rural areas.  
    - Correlation Heatmap – Heatmap showing correlations between numeric variables.

---

## How to Run
1. Open the notebook 'task2.ipynb' in Jupyter Notebook.  
2. Run all cells sequentially from top to bottom.  
3. Ensure the dataset CSV files are in the same folder as the notebook.

