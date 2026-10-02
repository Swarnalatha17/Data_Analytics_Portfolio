# Sales Forecasting & Analysis

## Project Overview

This project focuses on analyzing historical sales data and forecasting future monthly sales using Python. The analysis covers sales trends, profitability, regional performance, category performance, and sub-category performance.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn
- Jupyter Notebook

## Dataset

The project uses the Superstore sales dataset containing 9,994 records and 21 columns.

The dataset covers sales transactions from January 2014 to December 2017.

## Work Completed

- Inspected and prepared the sales dataset for analysis.
- Analyzed monthly and yearly sales trends.
- Compared sales performance across categories and regions.
- Analyzed sales across different sub-categories.
- Compared category and regional profitability.
- Examined the relationship between discount and profit.
- Calculated a 3-month moving average to study sales trends.
- Built a Holt-Winters Exponential Smoothing model to forecast future monthly sales.
- Evaluated the forecasting model using MAE and RMSE.

## Key Results

- Total Sales: **$2,297,200.86**
- Total Profit: **$286,397.02**
- Total Quantity Sold: **37,873**
- Average Order Sales: **$229.86**
- Highest Monthly Sales: **$118,447.82**
- Lowest Monthly Sales: **$4,519.89**
- Forecasted Sales for Next 6 Months: **$363,796.18**
- MAE: **7,319.85**
- RMSE: **9,083.47**

## Sales Analysis

Yearly sales increased from **$484,247.50 in 2014** to **$733,215.26 in 2017**.

Sales by category:

- Technology: **$836,154.03**
- Furniture: **$741,999.80**
- Office Supplies: **$719,047.03**

Sales by region:

- West: **$725,457.82**
- East: **$678,781.24**
- Central: **$501,239.89**
- South: **$391,721.91**

## Forecasting

Monthly sales were analyzed using a 3-month moving average before applying the forecasting model.

The model produced a six-month sales forecast for January to June 2018 with a combined forecast of approximately **$363,796.18**.

## Model Evaluation

The forecasting model was evaluated using:

- **Mean Absolute Error (MAE): 7,319.85**
- **Root Mean Squared Error (RMSE): 9,083.47**

These metrics were used to measure the difference between the model's predictions and the actual sales values.

## Key Learning

This project helped me practice working with time-based sales data, analyzing trends, creating moving averages, building a basic forecasting model, and evaluating forecasting results using Python.

## Project Files

- Jupyter Notebook containing the complete analysis and forecasting process.
- Dataset used for the analysis.
