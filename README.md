# Time-Series-Forecasting
## Objective 
The objective of this project is to forecast passangers screening for rest of the year in 2024 i.e from August to December at eight major Canadian Airports. Data for training and testing is for the past two years published weekly by https://www.catsa-acsta.gc.ca/en/screened-passenger-data

## Tech Stack
- Python(Pandas, Numpy , Sci-kit Learn, Statsmodel , Prophet)
- Power BI and DAX (for visualization)

## Models used for forecasting
- ARIMA and SARIMA
- Exponential Smoothening
- Prophet

## Parameters evaluated for accuracy
- Mean absolute error(MAE)
- Mean Squared error (MSE)
- Root mean squared error (RMSE)
- Mean absolute percentage error (MAPE)
- Mean Forecast Error (MFE)
- Mean Bias Percentage 

## Results and Analysis
- Arima / Sarima 
Despite data being stationary results were not satisfactory as suggested by the parameters (refer file [here](https://github.com/RimpleDabas/Time-Series-Forecasting/blob/main/ARIMA_SARIMAX.ipynb)) 
- Exponential Smoothening
![](Time Series Forecasting/Time-Series-Forecasting/Exponential Smoothening.png)


