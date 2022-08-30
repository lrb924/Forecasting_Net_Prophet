# Forecasting Net Prophet

### Package Requirments

`pip install x` where x is the below listed packages
* pystan=="2.19
* fbprophet
* hvPlot
* holoviews
* numpy
* pandas

### Purpose of Use
* In a bid to drive revenue, a Jupyter notebook was produced that contains the data preparation, analysis, and visualizations for all the time series data that the company needs to understand. Specifically, the notebook contains the following:
  * Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.
  * An evaluation of how the company stock price correlates to its Google Search traffic.
  * A Prophet forecast model that can predict hourly user search traffic.
* The analysis contains four parts:
  * Find Unusual Patterns in Hourly Google Search Traffic
  * Mine the Search Traffic Data for Seasonality
  * Relate the Search Traffic to Stock Price Patterns
  * Create a Time Series Model with Prophet

### Files Navigation
* `crypto_investments.ipynb`: Notebook containing all data analysis and visualization
* `crypto_market_data.csv`: Provided csv file containing crypto market data used in Notebook