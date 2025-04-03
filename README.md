# Wind-Power-Generation-Forecasting

# Overview

This repository contains a Jupyter Notebook for forecasting wind power generation using meteorological and wind-related data across multiple locations. The project leverages machine learning techniques to predict power output based on environmental conditions such as temperature, humidity, wind speed, and direction.

# Features

<b>1) Data Loading:</b> Reads datasets from multiple locations (Location1.csv, Location2.csv, Location3.csv, Location4.csv) containing weather and wind data.
<b>2) Data Preprocessing:</b> Includes steps for cleaning and standardizing data using tools like pandas and scikit-learn.
<b>3) Exploratory Data Analysis (EDA):</b> Visualizes trends and relationships in the data using matplotlib and seaborn.
<b>4) Machine Learning:</b> Prepares data for predictive modeling using techniques like feature scaling and splitting into training/testing sets.

# Dependencies

The notebook requires the following Python libraries:
1) pandas (v2.2.3)
2) numpy (v2.2.3)
3) scikit-learn (v1.6.1)
4) matplotlib (v3.10.1)
5) seaborn (v0.13.2)

# Data Description

The datasets include the following columns:
<b>Time:</b> Timestamp of the observation.
<b>temperature_2m:</b> Temperature at 2 meters above ground level.
<b>relativehumidity_2m:</b> Relative humidity at 2 meters.
<b>dewpoint_2m:</b> Dew point temperature at 2 meters.
<b>windspeed_10m & windspeed_100m:</b> Wind speed at 10 meters and 100 meters above ground.
<b>winddirection_10m & winddirection_100m:</b> Wind direction at 10 meters and 100 meters.
<b>windgusts_10m:</b> Wind gusts at 10 meters.
Power: Generated power output.

#Output
The notebook outputs:
1) Statistical summaries of the data.
2) Visualizations of key features affecting power generation.
3) Predictions of power output based on input features.
