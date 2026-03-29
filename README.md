## **Machine Learning Modeling of Outdoor Thermal Comfort (UTCI) in Southwestern Nigeria**

### Project Overview

This project develops a machine learning framework for modeling outdoor thermal comfort using the Universal Thermal Climate Index (UTCI) across Southwestern Nigeria.

The study leverages ERA5 reanalysis data and evaluates multiple machine learning models to capture non-linear relationships between meteorological variables and thermal comfort.

### Objectives

* Model UTCI using meteorological variables (T, RH, WS, SR)
* Compare performance of ML models (ANN, RF, XGBoost, Linear)
* Analyze feature importance
* Provide a scalable framework for climate applications

### Models Implemented

* Multiple Linear Regression
* Decision Tree
* Random Forest
* XGBoost
* Artificial Neural Network (MLP)

### Evaluation Metrics

* MAE
* RMSE
* R²

### Dataset

* Source: ERA5 (ECMWF)
* Resolution: 0.25° (~31 km)
* Period: 2011–2020
* Frequency: Hourly

 Note: Full dataset not included due to size.
You can access ERA5 data via:
[https://cds.climate.copernicus.eu/](https://cds.climate.copernicus.eu/)


### Methodology

* Data preprocessing & feature engineering
* UTCI computation using `pythermalcomfort`
* Time-aware train/validation/test split
* Model training & hyperparameter tuning (Optuna)
* Model evaluation and diagnostics

### Key Insights

* ANN achieved highest modeling accuracy
* Non-linear models outperform linear models
* Air temperature is the dominant driver of thermal comfort
* Coastal regions show slightly higher modeling errors


### ⚠️ Important Note

UTCI was derived from the same meteorological variables used as inputs.
Therefore, this work represents **functional modeling (surrogate modeling)** rather than prediction of an independent variable.
