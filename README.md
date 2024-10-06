Taxi Cab Ride Price Prediction




This project aims to predict taxi cab ride prices using a dataset enriched 
with multiple features such as datetime, distance, weather conditions, and surge information. 
The dataset has been preprocessed to extract useful features like hour,
day, month, day of the week, and year, which help capture temporal patterns.



Key Features:
Datetime-based features: Extracted hour, day, month, day_of_week, and year from ride timestamps.
Location data: Source and destination coordinates to account for distance-based pricing.
Weather conditions: Integrated weather data to capture the effect of weather on ride demand and pricing.
Surge information: Added surge pricing feature for times of high demand.
Models:
Random Forest
Gradient Boosting
Linear Regression
I explored different model architectures and performed hyperparameter tuning to optimize for prediction accuracy. 
This repository also includes model evaluation metrics, as well as visualizations of the prediction performance.
