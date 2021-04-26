# Unit-10_A_Yen_for_the_Future
-----


#### In this notebook, I will load historical Canadian Dollar-Yen exchange rate futures data and apply time series analysis and modeling to determine whether there is any predictable behavior.


Conclusions of Return Forecasting: Time Series Analysis & Modelling with CAD-PHY Exchange rate data.

Based on your time series analysis, would you buy the yen now?

Answer: 
p-value <0.05, forcast in the next 5 days the exchange rate will decrease and the exchange volatility forecast will increase. I will not buy the in the next 5 days
Is the risk of the yen expected to increase or decrease?
YOUR ANSWER HERE the risk of yen expected to increase, because the forecast volatility increased
Based on the model evaluation, would you feel confident in using these models for trading?
YOUR ANSWER HERE yes, but i will use the most recent data base to evaluate.

--------

#### In this notebook, I will build a SKLearn linear regression model to predict Yen futures ("settle") returns with *lagged* CAD/JPY exchange rate returns.

Conclusions of Regression Analysis: Seasonal Effects with Sklearn Linear Regression

Question: Does this model perform better or worse on out-of-sample data as compared to in-sample data?

Answer: 

Since Out-of-Sample Root Mean Squared Error (RMSE)is 0.64;In-sample Root Mean Squared Error (RMSE):0.84 the model perform a little bit better,but we expect a slightly higher out-of-sample RMSE, which is what we see.

