# 📊 E-Commerce Sales Performance & Analytical Pipeline

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/pandas-2.0%2B-darkblue.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/matplotlib-3.7%2B-orange.svg)](https://matplotlib.org/)

An automated, end-to-end data analysis pipeline engineered to process transactional retail data. This system programmatically manages the entire data lifecycle—from ingestion and structural validation to multi-variant statistical plotting and automated executive report generation.

---

## 📁 Repository Architecture

To maintain industry-standard clean code principles, the project uses a strictly isolated folder structure:

```text
├── data/
│   └── sales_data.csv                 # Raw input transactional dataset
├── visualizations/
│   ├── product_sales_bar.png          # Revenue comparison by product category
│   └── Monthly_Sales_Distribution.png # Month-over-month market share pie chart
├── report/
│   └── insights.txt                   # Programmatically generated performance report
├── main.py                            # Core pipeline execution script
├── README.md                          # Repository documentation & user guide
└── requirements.txt                   # Software package dependencies


## 📊 Visualizations Preview

### Categorical Sales Stream Breakdowns
![Product Sales Bar Chart](visualizations/product_sales_bar.png)

### Monthly Volume Distribution Dynamics
![Monthly Sales Distribution](visualizations/Monthly_Sales_Distribution.png)


## 🧪 Testing Evidence & Console Logs

```text
--- Data Loaded Successfully ---
Data is perfectly clean! No missing values found.

Total Sales: $170000
Total Profit: $39000

Both charts have been successfully saved to the 'visualizations/' folder!
The final report has been successfully saved to 'report/insights.txt'!
