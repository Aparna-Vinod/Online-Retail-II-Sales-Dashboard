# Interactive Online Retail II Sales Dashboard

## Project Overview

This project is about exploring retail sales data and understanding how an online store performs over time.

Using the Online Retail II dataset, I looked at sales trends, customer purchasing behaviour, and buying patterns across different countries. I used Python to clean the data, explore it, and create an interactive dashboard to present the findings.

## Dataset

**Dataset:** Online Retail II

**Source:** [UCI Machine Learning Repository – Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

The dataset contains transactions from a UK-based online gift retailer between December 2009 and December 2011.

It includes details such as:
- Invoice number
- Product code and description
- Quantity purchased
- Invoice date
- Unit price
- Customer ID
- Country

## Tools and Technologies

- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Plotly

## Project Workflow

I followed these steps to complete the project:

1. **Data Collection:** Downloaded the dataset from the UCI Machine Learning Repository.
2. **Data Cleaning:** Checked for missing values, duplicates, cancelled orders, and return transactions.
3. **Data Preparation:** Created additional features such as revenue and date-related columns.
4. **Data Analysis:** Explored sales trends, customer behaviour, and purchasing patterns.
5. **Visualisation:** Created different charts to understand the data more clearly.
6. **Dashboard Creation:** Combined the visualisations into an interactive dashboard and exported it as an HTML file.

## Dashboard Visualisations

The dashboard includes six visualisations:

1. Monthly Revenue Trend – Line Chart
2. Monthly Order Volume – Bar Chart
3. Order Value Distribution – Histogram
4. Customer Purchase Frequency vs Spending – Scatter Plot
5. Revenue Contribution by Country – Treemap
6. Purchasing Activity by Day and Hour – Heatmap

It also displays four key performance indicators:

- Gross Revenue
- Total Orders
- Unique Customers
- Unique Products

## Key Findings

A few interesting patterns I noticed during the analysis:

- Sales revenue changes from month to month, with noticeable peaks towards the end of the year.
- Most orders have relatively lower values, while a smaller number have much higher values.
- Some customers make more frequent purchases and spend considerably more than others.
- The United Kingdom accounts for the largest share of total revenue.
- Most purchasing activity takes place during daytime hours.

## Future Improvements

There are a few ways this project could be developed further:

- Add filters for different countries and date ranges.
- Explore product-level sales performance in more detail.
- Group customers based on their purchasing behaviour.
- Use predictive models to analyse future sales trends.

## Author

Created as part of my Data Analytics project using Python and interactive visualisation tools.
