# weather-prediction-for-Ahmedabad-and-Mumbai-city-
We performed a weather prediction analysis for Ahmedabad and Mumbai using the Seasonal Autoregressive Integrated Moving Average (SARIMA) model. This model is suitable for time series data with seasonal patterns, making it ideal for our task. We incorporated key weather variables such as precipitation, temperature, and humidity.

Methodology:

Data Collection: Gathered historical weather data for both cities, including daily precipitation, temperature, and humidity values.
Preprocessing: Cleaned the data to handle any missing values and outliers. Additionally, we performed seasonal decomposition to understand the inherent patterns in the data.

Modeling:

SARIMA Setup: Configured the SARIMA model parameters (p, d, q) and seasonal components (P, D, Q, m) for both cities.
Training: Trained the SARIMA model on historical data to learn the seasonal and non-seasonal patterns.
Validation: Validated the model using a portion of the historical data to ensure accuracy and reliability.
Prediction: Used the trained SARIMA model to forecast future values of precipitation, temperature, and humidity for both Ahmedabad and Mumbai.

Results:

Ahmedabad: The model captured the seasonal variations in temperature and humidity, providing reliable forecasts.
Mumbai: Given its unique weather patterns, particularly the monsoon season, the model effectively predicted the seasonal spikes in precipitation and changes in humidity.

Conclusion:

The SARIMA model proved to be effective in predicting weather patterns for both Ahmedabad and Mumbai. The forecasts can aid in planning and decision-making processes related to weather-dependent activities.
