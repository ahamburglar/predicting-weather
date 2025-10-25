# Predicting Local Weather Using Machine Learning 🌦️

## Overview

This project demonstrates a machine learning–based approach to predict local weather patterns using historical meteorological data.  
By leveraging data on temperature, humidity, pressure, and wind speed, the model estimates future weather outcomes and helps illustrate how data-driven insights can support environmental forecasting.

## Dataset

The dataset, **`local_weather.csv`**, contains locally collected weather records.  
Key features include:

- Temperature (°C)
- Humidity (%)
- Wind Speed (m/s)
- Atmospheric Pressure (hPa)
- Weather Condition (if categorical)

## Project Structure

```bash
📂 predicting-weather
│
├── predicting_weather_JOS_professional.ipynb   # Main Jupyter Notebook
├── local_weather.csv                           # Input dataset
└── README.md                                   # Project documentation
```

## Features

- Data cleaning and preprocessing  
- Exploratory data analysis (EDA) with statistics and visualizations  
- Machine learning model training and evaluation  
- Performance assessment using standard metrics  
- Clear and professional documentation

## How to Run

1. Install Python 3.8+  
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook predicting_weather_JOS_professional.ipynb
   ```

4. Run all cells to reproduce the analysis and results.

## Insights

- Identified correlations among weather variables  
- Developed a model to predict weather parameters with reasonable accuracy  
- Demonstrated potential to extend the approach to real-time prediction or dashboard deployment

## Next Steps

- Incorporate additional external datasets (e.g., satellite or regional weather data)  
- Test deep learning or time-series forecasting methods (LSTM, ARIMA)  
- Deploy as an interactive web dashboard

## Author

**Chang Liu**  
📍 Project created for data analysis and machine learning practice.
