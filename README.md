# Time Series Modelling and Forecasting

## 📊 Overview
This project applies statistical and time series techniques to model and forecast patterns in data.

The approach combines ARIMA for modelling the underlying structure and GARCH-type models to capture time-varying volatility.

The goal is to understand both the level and variability of the data, evaluate forecasting performance across different models, and assess whether differences in forecast accuracy are statistically significant.

---

## 🔹 Methodology

### 1. Mean Modelling
- An ARIMA(2,0,2) model was used to capture the underlying structure in the data
- This step isolates residuals for further analysis

### 2. Volatility Modelling
The residuals were modelled using:
- GARCH
- EGARCH
- GJR-GARCH

These models capture time-varying variability and asymmetric behaviour in the data.

---

## 🔹 Model Evaluation

Forecast performance was evaluated using:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Diebold–Mariano (DM) test for statistical comparison of forecast accuracy

**Result:**
- EGARCH produced the most accurate forecasts based on both MSE and MAE
Returns were computed as log-returns for time series modelling.
- The DM test was used to assess whether forecast differences between models were statistically significant

---
## 🔹 Data

The analysis was conducted using historical price data for Volkswagen AG, selected as a liquid and well-traded equity with observable volatility dynamics.
Returns were computed as log-returns for time series modelling.

----
## 🔹 Key Insights

- Data can exhibit changing variability over time (volatility clustering)
- Advanced models capture these dynamics more effectively
- Forecast evaluation should include both error metrics and formal statistical tests
- Model selection plays a critical role in forecasting accuracy

---

## 🔹 Skills Demonstrated

- Data Analysis and Cleaning
- Statistical Modelling
- Time Series Analysis
- Forecasting Techniques
- Model Evaluation and Comparison
- Hypothesis Testing
- Python (statsmodels, arch, etc.)

---

## 🔹 Relevance

This project demonstrates techniques applicable to:
- Financial risk modelling
- General time-dependent data modelling

---

## 🔹 Extensions

Potential improvements include:
- Machine learning approaches
- Non-linear models besides ARIMA MODELS
