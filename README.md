
#  Machine Learning Prediction of Outdoor Thermal Comfort

##  Project Overview
This project develops a machine learning framework to predict outdoor thermal comfort using the Universal Thermal Climate Index (UTCI) across Southwestern Nigeria.

The study uses ERA5 reanalysis data (2011–2020) and applies multiple machine learning models to capture complex, non-linear relationships between meteorological variables.


## Dataset
- Source: ERA5 (ECMWF)
- Time range: 2011–2020 (hourly)
- Variables:
  - Air Temperature (T)
  - Relative Humidity (RH)
  - Wind Speed (WS)
  - Solar Radiation (SR)

##  Models Implemented
- Artificial Neural Network (ANN)
- Random Forest
- XGBoost
- Linear Regression
- Decision Tree


## Key Results
- ANN achieved the highest accuracy (lowest RMSE, highest R²)
- Ensemble models showed strong performance
- Thermal comfort is highly non-linear
- Air temperature is the dominant predictor

```bash
git clone https://github.com/yourusername/thermal-comfort-ml.git
cd thermal-comfort-ml
