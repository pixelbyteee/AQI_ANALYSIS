📌 Introduction

Air quality significantly impacts public health and the environment, making it a crucial concern, particularly in urban areas. The Air Quality Index (AQI) provides a standardized method for calculating and communicating air pollution levels. Accurate AQI estimation is essential for effective decision-making in environmental policy and public health.This project utilizes machine learning techniques to develop an AQI prediction model for Indian cities, incorporating various pollutants such as PM2.5, PM10, NO2, and CO.

📊 Dataset
https://www.kaggle.com/datasets/hirenvora/city-daycsv
The dataset includes air pollution data from multiple Indian cities. Key pollutants considered for AQI estimation:
PM2.5 (Particulate Matter ≤2.5µm)
PM10 (Particulate Matter ≤10µm)
NO2 (Nitrogen Dioxide)
CO (Carbon Monoxide)

🔍 Methodology
To determine the best AQI prediction model, we tested 11 different machine learning models, including:
Linear Regression
Ridge Regression
ElasticNet
Support Vector Regression (SVR)
Gradient Boosting
Random Forest
XGBoost
The models were evaluated using R² scores on training, validation, and test datasets to determine their effectiveness.

🏆 Results
Model         R² Score
Random Forest-0.9583
XGBoost -0.9227
Gradient Boosting-0.8441
Linear Regression-Poor Performance

Random Forest and XGBoost performed the best, showing strong predictive capabilities.
Gradient Boosting also achieved decent results.
Linear regression-based models performed poorly, highlighting their limitations in modeling air pollution.

📌 Key Insights

✔ PM2.5 and PM10 are the most significant contributors to AQI estimation.
✔ Machine learning models effectively predict AQI and can aid urban planning and environmental policies.
✔ Simple models are insufficient, while ensemble-based methods (Random Forest, XGBoost) perform better.

🚀 Future Scope

🔹 Real-time data integration for continuous AQI monitoring.
🔹 Incorporating weather conditions (temperature, humidity, wind speed).
🔹 Deep learning models for enhanced prediction accuracy.
🔹 Deployment as a web application or API for public use.
