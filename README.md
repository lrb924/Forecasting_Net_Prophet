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
* Resources: Directory containing all necessary csv files
* `forecasting_net_prophet.ipynb`: Notebook containing all data analysis and visualization

### Solution
Did the Google search traffic increase during the month that MercadoLibre released its financial results?
* Yes, the search traffic increased during the month MercacdoLibre released its financial results.

Does any day-of-week effect that you observe concentrate in just a few hours of that day?
* Yes, there are a few hours (mainly in the middle of the night) on certain days that search traffic was increased and concentrated for that day.

Does the search traffic tend to increase during the winter holiday period (weeks 40 through 52)?
* Yes, the search traffic increased during weeks 40 through 52.

Do both time series indicate a common trend that’s consistent with the narrative that both e-commerce and search traffic increased after the initial shock to global financial markets?
* Yes, when the stock price went down so did search traffic. The opposite was also true around mid-May 2020: when the closing price increased, the search traffic also increased.

Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?
* A predictable relationship exists between the lagged search traffic and the stock price returns.

What time of day exhibits the greatest popularity?
* Around midnight

Which day of the week gets the most search traffic?
* Tuesdays

What's the lowest point for search traffic in the calendar year?
* Around mid-October
