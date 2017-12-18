# Wind Energy Forecast

It is a multivariate time series which is challenging to forecast.

## Approach

+ Data Analysis 
+ Imputing missing values
+ Model building 
1. Simple Univariate Auto regression model .
2. Simple Linear regression model with explantory variables

+ Model evaluation using Multi step forecasting (Forward rolling suing Timeseries split)

+ Ensemble the predictions from both Model 

## Model Evaluation 

+ Time series cross-validation
In this procedure, there is a series of test sets, each consisting of a single observation. The corresponding training set consists only of observations that occurred prior to the observation that forms the test set. Thus, no future observations can be used in constructing the forecast. The following diagram illustrates the series of training and test sets, where the blue observations form the training sets, and the red observations form the test sets.

![alt tag](https://github.com/MuaazBin/multi_tsa/blob/master/imgs/cv_time.png)

** Reference: https://robjhyndman.com/hyndsight/tscv/ **

## Future Work

+ Combine ML and Time series model predictions
+ Use sliding window from last week & last year
+ Use feature extractors like tslearn /hctsa and use supervised ML
+ Work with LSTM models

## Libraries Used

+ Pandas
+ Scikit Learn
+ Facebook Prophet
+ stats tsa

## LIbraries to try next

+ tslearn
+ pyopy
+ keras

