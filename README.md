# Wind-Power-Generation-Forecasting

#Overview
This repository contains a Jupyter Notebook for forecasting wind power generation using meteorological and wind-related data across multiple locations. The project leverages machine learning techniques to predict power output based on environmental conditions such as temperature, humidity, wind speed, and direction.

#Features
Data Loading: Reads datasets from multiple locations (Location1.csv, Location2.csv, Location3.csv, Location4.csv) containing weather and wind data.
Data Preprocessing: Includes steps for cleaning and standardizing data using tools like pandas and scikit-learn.
Exploratory Data Analysis (EDA): Visualizes trends and relationships in the data using matplotlib and seaborn.
Machine Learning: Prepares data for predictive modeling using techniques like feature scaling and splitting into training/testing sets.

#Dependencies
The notebook requires the following Python libraries:
pandas (v2.2.3)
numpy (v2.2.3)
scikit-learn (v1.6.1)
matplotlib (v3.10.1)
seaborn (v0.13.2)
To install all dependencies, run:

#Data Description
The datasets include the following columns:
#Time: Timestamp of the observation.
temperature_2m: Temperature at 2 meters above ground level.
relativehumidity_2m: Relative humidity at 2 meters.
dewpoint_2m: Dew point temperature at 2 meters.
windspeed_10m & windspeed_100m: Wind speed at 10 meters and 100 meters above ground.
winddirection_10m & winddirection_100m: Wind direction at 10 meters and 100 meters.
windgusts_10m: Wind gusts at 10 meters.
Power: Generated power output.

#Output
The notebook outputs:
1) Statistical summaries of the data.
2) Visualizations of key features affecting power generation.
3) Predictions of power output based on input features.
