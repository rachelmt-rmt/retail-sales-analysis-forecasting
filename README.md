# Retail Sales Analysis & Time-Series Forecasting

## Project Overview

This project analysed retail sales data using Python and SQL within Microsoft Fabric.

The analysis involved querying data from a relational database, combining sales, invoice and product information, conducting exploratory data analysis, and analysing sales patterns across products and countries.

The project also introduced time-series forecasting using ARIMA to predict future monthly sales.

## Tools & Technologies

- Python
- Pandas
- SQL
- Azure SQL
- Microsoft Fabric
- Matplotlib
- ARIMA

## Data Preparation

Data was retrieved from three relational database tables:

- Sales
- Invoice
- Product

The tables were queried from an Azure SQL database and loaded into Pandas DataFrames.

The datasets were then merged using common identifiers:

- Sales and Invoice data were joined using `InvoiceNo`
- Product information was added using `StockCode`

A new `Sales` variable was calculated using:

`Sales = Quantity × UnitPrice`

## Exploratory Data Analysis

Exploratory analysis included:

- Checking for missing values
- Reviewing descriptive statistics
- Examining data types
- Exploring product-category distributions
- Analysing sales across countries
- Aggregating sales data for further analysis

Visualisations were used to explore patterns and communicate findings.

## Time-Series Forecasting

Sales data was aggregated by month to create a chronological time series.

The data was divided into training and testing periods while maintaining chronological order.

An ARIMA model was then used to forecast sales for the test period.

Model predictions were compared with actual sales values and evaluated using Root Mean Squared Error (RMSE).

## Skills Demonstrated

This project demonstrates my ability to:

- Query relational databases using SQL
- Work with Azure SQL data
- Load SQL query results into Pandas
- Join and merge relational datasets
- Clean and explore data using Python and Pandas
- Create calculated variables
- Aggregate and analyse sales data
- Create data visualisations
- Prepare chronological time-series data
- Develop an ARIMA forecasting model
- Compare actual and predicted values
- Evaluate model performance using RMSE
- Work within Microsoft Fabric

## Repository Files

- `Retail_Sales_Analysis_Forecasting.ipynb` – data querying, exploratory analysis and time-series forecasting notebook
