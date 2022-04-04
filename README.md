# Time_Series
The main objective of this work is to develop a prediction model that will support the planning decisions of health authorities regarding preventive medicine protocols based on the pollution index that will be predicted by the model. Based on fluctuating air quality index values, health authorities can set guidelines for health services and alert civilians to practices that mitigate the effects of pollution.

Through univariate and multivariate stochastic models and neural networks, we intend to predict the value of an unknown variable (AQI) by analyzing the other variables. The models can then predict the value of the Air Quality Index taking into account the values of Benzene, Carbon Disulfide, Ozone, Sulfur Dioxide, Toluene, Xylene, wind direction, speed and origin for the multivariate models. On the other hand, univariate models use the AQI, calculated using ozone to make the forecast.

Graphical analysis indicates that the SARIMA and AUTO_ARIMA models are not good at making predictions. While LSTM models have approximate predictions from the test set.
