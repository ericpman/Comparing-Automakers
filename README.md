# Stock Analysis of Tesla, Ford, and General Motors
## This project analyzes and visualizes the stock performance of Tesla (TSLA), Ford (F), and General Motors (GM) from January 1, 2012, to January 1, 2024. The data was obtained using the yfinance library, and analysis includes daily returns, cumulative returns, trading volume, and moving averages, among other metrics. The project is designed to provide a comparative view of these companies' stock performance over time.

### Project Overview
This project examines:

Daily Open prices, Volume of shares traded, Total traded value (product of Open price and Volume), Moving averages (50-day and 200-day), Daily and cumulative returns, Relationships between companies’ daily returns using scatter plots, histograms, and kernel density estimates.

### Data Collection
The data for this project is sourced from Yahoo Finance using the yfinance library. We focus on stock data for Tesla, Ford, and General Motors within the specified date range, which is set at the beginning of the script.

### Analysis and Visualizations
The analysis consists of the following parts:

#### Daily Open Price Plot: 
Plots the opening prices for Tesla, Ford, and GM to show the comparative price changes over time.

#### Volume Traded Plot: 
Plots daily trading volume for each stock, highlighting the date of highest trading volume for Ford.

#### Total Traded Value Plot: 
Calculates and plots the daily trading value (Open price × Volume) for each stock to compare trading activity.

#### Moving Averages: 
Calculates and plots the 50-day and 200-day moving averages for GM to illustrate long-term trends.

#### Daily Returns:

Computes the daily percentage returns for each stock and visualizes the distribution of returns using histograms.
Plots kernel density estimates (KDE) for each stock’s returns to show a smoothed distribution.

#### Return Distribution:

Box plot of daily returns for Tesla, Ford, and GM to display median, quartiles, and outliers.
Scatter matrix (pair plot) for visualizing correlations between the returns of these companies.

#### Cumulative Returns: 

Calculates and plots the cumulative returns for each stock, illustrating the growth of an initial investment over the period analyzed.

#### Additional Candlestick Chart for Ford:

Uses the mplfinance library to generate a candlestick chart for Ford during January 2012.


#### Setup:

Ensure all required libraries are installed (see Dependencies).
Adjust the start and end date variables if you want to analyze a different date range.

#### Run the Code:

Run each cell sequentially to perform the analysis and generate the visualizations.
Modify plotting parameters as desired for customization.

#### Visualizations:

View each plot as it is generated to understand the comparative performance of each stock.

#### Libraries: 

pandas for data manipulation
matplotlib for plotting
numpy for numerical operations
yfinance for stock data retrieval
mplfinance for candlestick charts
