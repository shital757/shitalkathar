# Shital_project
This notebook analyzes Bitcoin exchange data from 2012 to 2017, focusing on the weighted price in USD. The data is resampled to daily, monthly, quarterly, and annual frequencies, and various visualizations are generated. Seasonal decomposition and Dickey-Fuller tests are used to assess stationarity. Box-Cox transformations and seasonal differencing are applied to stabilize variance and remove seasonality. Autocorrelation and partial autocorrelation plots help in initial parameter estimation for bitcoin models. The best model is selected based on the lowest AIC value, and its residuals are analyzed for stationarity. Finally, the model is used to forecast future Bitcoin prices, showing a reasonable predictive capability.

*Conclusion:* The model effectively captures the seasonal patterns in Bitcoin prices, and the predicted values align well with the observed data, suggesting the model's utility for forecasting.
