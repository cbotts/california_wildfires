# Predicting California Wildfires 
A time series analysis

## Objective
Use time series analysis to predict the numbers of acres that will burn from wildfires in California. 

## How to Run 
```
git clone https://github.com/cbotts/california_wildfires/
jupyter notebook /california_wildfires/Botts_Project1.ipynb
```

## Data 
Instances of California wildfires from the years 2013-2020. The data does not include the entirety of the year 2020.


Source: https://www.kaggle.com/datasets/ananthu017/california-wildfire-incidents-20132020

## Methods 
SARIMA and ARIMA models were built and compared for the best predictive capability of future wildfires. This was a univariate analysis. 

## Conclusion 
Results for the number of acres burned are the most accurate when modeled as a monthly aggregation. 
This model is limited and has weak predictive power. It is recommended to supplement the dataset with additional features, specifically weather data to improve predictive power.
