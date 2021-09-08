# Conclusions


### Based on your time series analysis, would you buy the yen now?

### Is the risk of the yen expected to increase or decrease?

### Based on the model evaluation, would you feel confident in using these models for trading?

Based on our time series analysis, it would make sense to buy the yen now, with anticipation that it will rise further over the next five days. However, risk (up or down volatile movements) is also forecast to rise, so even if we're right, there might be some days in the interim where we see larger than usual swings in the price. 

Overall, our model for forecasting volatility looks reasonably solid. However, our models for predicting future yen returns (ARMA) and for yen prices (ARIMA) seem like they could use some improvement before we actually start using them to make financial bets. This is because none of the features included in the model (i.e., the lags) were significant, as all had p-values well above 0.05.

# Regression Analysis 

Overall, our model has an root mean squared error of 0.415% on the out-of-sample data, and 0.566% on the in-sample data. This means that the model actually performs slightly better on data that it hasn't seen before. 

Generally however (though not always), we should expect a higher error rate on the out-of-sample data than the in-sample data, since the model is specifically trained to predict the in-sample data as well as it can. It's possible that if we continued adding additional data as time goes on, out-of-sample performance may not continue to be as good (so out-of-sample RMSE may rise).