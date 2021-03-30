# Time-Series-Models

The prediction of electric load is a task that can allow generators to decide how much production to ramp up, consumers to estimate electricity prices, and the grid operator to make sure enough transmission capacity is available.

We are using 4-year electrical consumption, generation, pricing, and weather data for Spain from https://www.kaggle.com/nicholasjhana/energy-consumption-generation-prices-and-weather to build up time series models to predict future electric load using the previously observed values and features like weather.

Models proposed and implemented:
1. Predict same demand as 24h ago (Baseline Model).
2. Autoregressive Model, and use previous 48 hours to predict next 24 hours.
3. Linear regression.
4. MLP.
5. LSTM, and use previous 48 hours to predict next 24 hours.
6. GRU, and use previous 48 hours to predict next 24 hours.
7. Convert time series forcasting into a supervised learning problem and add weather feature to predict.
8. Ensemble.
