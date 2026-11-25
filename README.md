# Interactive Online Retail II Sales Dashboard

## Project Overview

This project presents an interactive sales analysis dashboard using the Online Retail II dataset from the UCI Machine Learning Repository.

The objective is to analyse retail transaction data and identify patterns in sales performance, customer purchasing behaviour, product demand, and purchasing activity over time.

The project uses Python for data cleaning, exploratory data analysis, visualisation, and dashboard development.

## Dataset

**Dataset:** Online Retail II

**Source:** [UCI Machine Learning Repository – Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

The dataset contains transactions from a UK-based online retail business between December 2009 and December 2011.

The dataset includes:
- Invoice number
- Product code
- Product description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

## Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

## Project Workflow

1. **Data Collection:** Obtained the Online Retail II dataset from the UCI repository.
2. **Data Cleaning:** Handled missing values, duplicate records, invalid prices, cancellations, and returns.
3. **Feature Engineering:** Created revenue, date-related features, and analytical summaries.
4. **Exploratory Data Analysis:** Examined sales trends, customer behaviour, and purchasing patterns.
5. **Dashboard Development:** Created an interactive dashboard using Plotly.
6. **Export:** Exported the completed dashboard as an HTML file.

## Dashboard Visualisations

The dashboard contains six main visualisations:

1. Monthly Revenue Trend – Line Chart
2. Monthly Order Volume – Bar Chart
3. Distribution of Order Values – Histogram
4. Customer Purchase Frequency vs Spending – Scatter Plot
5. Revenue Contribution by Country – Treemap
6. Purchasing Activity by Day and Hour – Heatmap

The dashboard also includes four key performance indicators:

- Gross Revenue
- Total Orders
- Unique Customers
- Unique Products

## Key Findings

The analysis highlights several patterns:

- Revenue fluctuates across the months, with noticeable peaks towards the end of the year.
- Order values are right-skewed, indicating that most orders have relatively lower values.
- A small number of customers account for substantially higher spending.
- The United Kingdom contributes the largest share of total revenue.
- Purchasing activity is concentrated mainly during daytime hours.

These observations are based on the cleaned sales records used in the analysis.

## Project Files

| File | Description |
|---|---|
| `Online_Retail_II_Sales_Dashboard.ipynb` | Complete Python analysis notebook |
| `online_retail_II_dashboard.html` | Interactive dashboard |
| `README.md` | Project documentation |
| `requirements.txt` | Python dependencies |

## How to Run

1. Download or clone this repository.
2. Open the notebook using Google Colab or Jupyter Notebook.
3. Download the dataset from the UCI Machine Learning Repository.
4. Run the notebook cells in sequence.
5. Open `online_retail_II_dashboard.html` in a web browser to explore the dashboard.

An internet connection is required to load the Plotly charts in the exported HTML dashboard.

## Future Improvements

- Add interactive filters for country and date range.
- Introduce product-level performance analysis.
- Develop customer segmentation using clustering.
- Add predictive sales analysis.

## Author

Created as a Data Analytics project using Python and interactive visualisation tools.
