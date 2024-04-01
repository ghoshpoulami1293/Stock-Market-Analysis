# Stock-Market-Analysis

This project is used to analyze and pmake prediction of stock prices for four technology companies: Apple (AAPL), Google (GOOG), Microsoft (MSFT), and Amazon (AMZN). 

The necessary libraries are imported including pandas, numpy, matplotlib, seaborn, and scikit-learn. 
The stock data for the specified companies is fetched using Yahoo Finance API. Data for the past year is retrieved.

Data Analysis and Visualization 
    Descriptive statistics like mean, min, max, etc., are printed for Apple's stock (AAPL).
    Historical closing prices and sales volume for each company are plotted.
    Moving averages for different periods (10, 20, and 50 days) are calculated and plotted.
    Daily returns for each company are calculated and plotted.
    Histograms of daily returns for each company are plotted.
    Pair plots and correlation heatmaps are generated to analyze relationships between daily returns of different companies.
    Risk Analysis: Scatter plot is created to visualize the relationship between expected return and risk for each company.

Predictive Modeling using ARIMA
    The ARIMA (AutoRegressive Integrated Moving Average) model is trained for each company using its closing stock prices.
    Predictions are made for future stock prices using the trained ARIMA models.
    Predictions are then plotted alongside actual stock prices for visual comparison.

The aim of the project is to provide insights into the performance and behavior of the selected tech stocks and to forecast their future price movements.