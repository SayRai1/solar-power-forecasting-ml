# Solar Power Forecasting with Machine Learning

Data science project that predicts the power output of two solar power plants
from weather sensor data.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)

## Data

| File | Content |
|------|---------|
| `Plant_1_Generation_Data.csv`, `Plant_2_Generation_Data.csv` | DC/AC power from each inverter |
| `Plant_1_Weather_Sensor_Data.csv`, `Plant_2_Weather_Sensor_Data.csv` | Irradiation, ambient and module temperature |
| `Plant_Prediction_Data_Grouped.csv` | Cleaned and merged dataset used for training |

## Notebooks

1. `Dataset_plant_sola.ipynb`: cleaning, merging generation and weather data, exploratory analysis
2. `Train_model_sola.ipynb`: regression models (scikit-learn, statsmodels), evaluated with R² and RMSE

## Author

Sirapop Poonkaew, Control Systems & Instrumentation Engineering, KMUTT
