# Data-Codes-LSTM-ARIMA
Temperature Prediction using Time Series Forecasting with ARIMA Model
The Average temperature of a city is required to be predicted using ARIMA model, monthly temperature of a city was obtained from kaggle.
The data was checked for its stationary property using adfuller to calculate p-value and it was >>> 0.05.
The model was then trained on the dataset to obtain the required order of ARIMA and is then fitted on the training data.
Model predicted average temperature for the next 30 days using the same constraints.
The accuracy and metrics of the model was rather satisfying as the RMSE was around 2 degrees.
