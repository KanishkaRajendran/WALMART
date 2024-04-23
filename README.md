# Walmart Sales Analysis Project

This project analyzes weekly sales data from Walmart stores using Python. The dataset includes information such as store details, dates, weekly sales, holiday flags, temperature, fuel prices, CPI, and unemployment.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- statsmodels

Install the required packages using the following command:

```bash
pip install pandas numpy matplotlib statsmodels
```

## Overview

**Data Loading and Preprocessing:**

Reads Walmart dataset from 'Walmart Dataset.csv'.
Sets the 'Date' column as the index.
User input for selecting a specific store.

**Time Series Plotting:**

Plots weekly sales data for the selected store.
Performs seasonal decomposition for trend, seasonality, and residuals.

**Comparison of Two Stores (Store 4 and Store 5):**

Plots weekly sales data for Store 4 and Store 5 in 2012.
Compares sales between the two stores.

**Time Series Analysis using SARIMA Model:**

Defines SARIMA model parameters.
Fits the model to the time series data.
Prints model summary.

**One-step ahead Forecasting:**

Makes one-step-ahead forecasts.
Plots forecasts against observed values.
Computes Mean Squared Error (MSE) for forecasts.

**Dynamic Forecasting:**

Performs dynamic forecasting.
Plots dynamic forecasts along with confidence intervals.
Computes Root Mean Squared Error (RMSE) for dynamic forecasts.

**12 Weeks Ahead Forecast:**

Makes forecasts for the next 12 weeks.
Plots forecasted values with confidence intervals.

**Residual Analysis:**

Computes sum of absolute residuals for dynamic forecasting.
