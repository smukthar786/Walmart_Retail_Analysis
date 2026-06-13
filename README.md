# Walmart Retail Sales Analysis

## Project Overview

This project analyzes Walmart retail sales data using Python to uncover sales trends, profitability patterns, product category performance, and regional business insights. The analysis includes data cleaning, preprocessing, exploratory data analysis (EDA), and data visualization to support data-driven decision-making.

## Objectives

* Analyze sales and profit performance across different product categories.
* Identify regional sales trends and market performance.
* Examine relationships between sales, profit, discounts, and other business variables.
* Generate actionable insights through data visualization.
* Demonstrate an end-to-end data analytics workflow using Python.

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook

## Dataset Information

**Dataset:** https://data.world/ahmedmnif150/walmart-retail-dataset

**Dataset Size:**

* 1,037,247 Rows
* 23 Columns

### Key Features

* Order Date
* Customer ID
* Product Category
* Sales
* Profit
* Quantity
* Discount
* Unit Price
* Shipping Cost
* Region
* State
* City
* Shipping Mode

## Project Workflow

### 1. Data Loading

* Imported the dataset using Pandas.
* Verified dataset structure and dimensions.

### 2. Data Cleaning and Preprocessing

* Converted date columns to datetime format.
* Filtered records from 2021 onwards.
* Handled missing values.
* Removed duplicate records.
* Standardized text values.
* Performed final validation checks.

### 3. Exploratory Data Analysis (EDA)

* Sales distribution analysis.
* Profit distribution analysis.
* Product category performance analysis.
* Regional sales comparison.
* Correlation analysis among numerical variables.

### 4. Data Visualization

The project includes various visualizations such as:

* Sales Distribution Analysis
* Profit Distribution Analysis
* Product Category Distribution
* Average Profit Margin by Product Category
* Regional Sales Comparison
* Product Category Distribution Across Regions
* Discount vs Profit Relationship
* Correlation Heatmap
* Interactive Plotly Visualizations
* Animated Sales by Product Category Over Time

## Key Insights

* Most sales transactions are concentrated within lower sales ranges.
* Office Supplies recorded the highest transaction volume among product categories.
* East and Central regions generated the highest sales volumes.
* Profitability varies significantly across transactions.
* Sales and profit exhibit a positive relationship.
* Discounts show only a weak correlation with profit, indicating that additional factors influence profitability.

## Project Structure

```
├── Walmart-Retail-Dataset.csv
├── Walmart-Retail-Analysis.ipynb
├── Walmart-Retail-Analysis-Documentation.pdf
├── Walmart_logo.png
└── README.md
```

## How to Run

1. Clone this repository.
2. Open the Jupyter Notebook.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn plotly
```

4. Run the notebook cells sequentially.
5. Explore the visualizations and insights generated during the analysis.

## Conclusion

This project demonstrates a complete data analytics workflow, from data preprocessing and exploratory analysis to visualization and insight generation. The findings provide valuable information about sales performance, profitability, and regional trends, showcasing how data analytics can support informed business decisions.

---

**Skills Demonstrated:** Data Cleaning • Data Preprocessing • Exploratory Data Analysis (EDA) • Data Visualization • Business Insight Generation • Python Analytics
