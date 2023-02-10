# S&P Price Time Series Analysis

### S&P price (time series data) from 1994 to 2018

1) examined the price trend 

2) examined stationarity and seasonality of the market price
- **Dickey-Fuller Test** for stationarity
- **Naive Decompsition (Additive and Multiplicative)** for Seasonality

3) conducted a statistical testing
- ACF (Autocorrelation) to see a calculated value used to represent how similar a value within a time series is to a previous value

4) conducted the Autoregression Model (AR)
- AR: Autoregression. A model that uses the dependent relationship between an observation and some number of lagged observations. 
- I: Integrated. The use of differencing of raw observations (e.g. subtracting an observation from an observation at the previous time step) in order to make the time series stationary. 
- MA: Moving Average. A model that uses the dependency between an observation and a residual error from a moving average model applied to lagged observations. Each of these components are explicitly specified in the model as a parameter. A standard notation is used of ARIMA(p,d,q) where the parameters are substituted with integer values to quickly indicate the specific ARIMA model being used.

5) conducted Log-Likelyhood LLR test
