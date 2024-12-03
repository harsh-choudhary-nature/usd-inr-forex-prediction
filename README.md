# USD INR Forex rate Prediction

## Abstract

This report presents a comparative analysis of multiple predictive models for time series forecasting, specifically applied to a 30-day forecast task of USD/INR rate. The models assessed include ARIMA, SARIMA, LSTM, and XGBoost, as well as an ensemble approach combining all three models with weighted contributions of 0.7 for ARIMA(2,1,2), 0.2 for LSTM, and 0.1 for XGBoost. Performance metrics such as RMSE and MAE were used to compare individual model accuracy, and information criterion like AIC and SBC were used to choose parsimonious models. Statistical tests, such as the ADF for stationarity, the ARCH-LM test for heteroskedasticity, and GARCH modeling for volatility, were applied to enhance insights into the data’s characteristics. Additionally, the binary segmentation method (binseg) detected structural breaks, which informed model adjustments.

The ARIMA model showed robust performance with a test RMSE of 0.2049, while XGBoost yielded the lowest RMSE of 0.0841. Despite its relatively high complexity, the LSTM model demonstrated a test RMSE of 0.6486. The ensemble model, integrating strengths from each individual model, achieved a forecast RMSE of 0.1808, indicating that an ensemble approach can leverage diverse predictive capacities to enhance forecast accuracy. This study highlights the efficacy of ensemble methods in improving forecasting reliability, making it a valuable approach for complex time series predictions.

**Keywords**: ADF, AIC, ARIMA, Binseg, Ensemble, GARCH, LSTM, SARIMA, SBC, XGBoost

## Code File

The code of the project is cumulated into a single python notebook. All the models are discussed therein. The file is called <a href = "">ensemble.ipynb</a>.
