# Power-Load-Forecasting
Power Load consumption forecasting: a comparison between classical statistical models (ARIMA and Exponential Smoothing) and Machine Learning models (LSTM and Random Forest)

## Description
The ultimate objective of this project is to compare ARIMA (AutoRegressive Integrated Moving Average) model, Exponential Smoothing model, LSTM and Random Forest models, in a widely known task: predicting a univariate time series.

Specifically, the subject of prediction will be daily power load consumption in Italy. The observations used for analysis span a time period of 17 years, starting from January 1, 2006, to December 31, 2022.
The dataset is checked for missing values and anomalies, any missing data has been filled using interpolation.

I conducted an EDA(Exploratory Data Analysis) in order to capture patterns like trend, seasonality and volatility; in addition, this analysis highlighted the very clear consequences on electricity consumption caused by the Covid 19 pandemic.

For the purpose of the project objective, I excluded observations from 2020 to 2022 and used data from 2006 to 2018 as training data, to predict those of 2019.
Next, I applied the ARIMA, Exponential Smoothing, Long Short Term Memory and Random Forest models to compare predictive performance.

## Results

