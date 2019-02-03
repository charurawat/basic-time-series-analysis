# timeseriesanalysis

## Basic Time Series Analysis
(DS 6001 , Dec 2018)

This analysis was performed using airline passenger data from -
https://datamarket.com/data/set/22u3/international-airline-passengers-monthly-totals-in-thousands-jan-49-dec-60#!ds=22u3&display=line

The idea was to use this data to analyse and understand components of time series data such as trend, seasonality,etc.

The code contains the following steps -

1. Create a date-time index for the data and plot the time series.
2. Use seasonal decompose from statsmodels to show the the trend, seasonality and random components, as well as, the original series.
3. Plot 3, 6 and 12 month moving averages overlaid on the original series.
4. Plot differences of 1, 3, 6, and 12 months overlaid on the original series.
5. Plot the simple exponential moving average overlaid on the original series.
