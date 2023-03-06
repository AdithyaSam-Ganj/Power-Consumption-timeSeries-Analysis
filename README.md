# Power-Consumption-timeSeries-Analysis



In this project I look at german power consumption data over a decade from 2006 to 2017. <br />
I try to predict the power consumption and also look at the seasonal trends in it. <br />
I even study the impact of introducing solar and wind energy into the power grid. <br />
I have even looked at the moving average and auto correlation to look at the general trend of thet data.

### Prediction Models 
I have used **linear regression, MLPRegressor, K-nearest Neighbours, Random forest regressor and Support Vector Machines** 
to test for the best model that fits the data. <br />
I used time series cross validation for robust validation of model. <br />
Obtained best results for random forest model with an **explained variance of 0.913 and RMSE of 0.037**.<br />
A **mean absolute error of 29.08** GWh was also obtained.  
