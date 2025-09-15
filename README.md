# Overview
This project explores **time series forecasting** using the Holt-Winters exponential smoothing method. The dataset exhibits a clear upward **trend**, **seasonality**, and **increasing variance** over time. To address this, the series is decomposed into components and modeled using the **multiplicative Holt-Winters method**.

# Objectives
1. Analyze time series characteristics (trend, seasonality, variance).
2. Apply decomposition to identify underlying patterns.
3. Implement single, double, and triple exponential smoothing.
4. Evaluate model accuracy using MSE.
5. Generate forecasts for the next 24 months with visualization.

# Data
The dataset used in this project is the **Passenger Data for Time Series Analysis** from [Kaggle](https://www.kaggle.com/datasets/ashfakyeafi/air-passenger-data-for-time-series-analysis).\
It contains the monthly total number of airline passengers from **January 1949 to December 1960** (144 observations).

**Frequency:** Monthly\
**Variables:**
* *Month* – date of observation
* *Passengers* – number of airline passengers


# Results
* Trend and 12-month seasonality were identified in the data
* The multiplicative Holt-Winters model provided the most accurate forecasts
* 24-month forecast plot:
  
  <img width="1189" height="690" alt="image" src="https://github.com/user-attachments/assets/41f3643d-3216-40b9-b4ac-52bdebea72c4" />
