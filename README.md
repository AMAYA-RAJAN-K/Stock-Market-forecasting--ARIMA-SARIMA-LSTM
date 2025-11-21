# Stock-Market-forecasting--ARIMA-SARIMA-LSTM
Machine Learning
Overview

This internship project focuses on building a complete stock price forecasting pipeline using real-time financial data. The project forecasts Apple Inc. (AAPL) closing prices using classical statistical models and deep learning architectures. It highlights industry-relevant competencies in financial time-series analysis, feature engineering, forecasting, performance evaluation, and model comparison.

## Objectives

To analyze historical AAPL stock data and forecast future closing prices.

To explore the effectiveness of ARIMA, SARIMA, and LSTM models.

To evaluate the models using standard forecasting metrics (RMSE, MAE, MAPE).

To identify insights from model behavior and visual outputs.

## Techniques & Software Used
Techniques

### ARIMA – Trend-based statistical forecasting model

### SARIMA – Seasonality-enhanced extension of ARIMA

### LSTM – Deep learning sequence model capable of learning long-term dependencies

## Software & Libraries

* Python

* Pandas, NumPy, Matplotlib, Seaborn

* Statsmodels (ARIMA/SARIMA)

* Scikit-learn (preprocessing, metrics)

* TensorFlow/Keras (LSTM)

* YFinance (stock data extraction)

## Relevance of the Project

* In today’s data-driven world, accurate stock market forecasting is essential for:

* Investment decision support

* Algorithmic trading systems

* Portfolio optimization

* Financial risk management

* Corporate financial strategy

* Time-series forecasting using ML and DL has become a core skill in finance, data science, and quantitative analysis.

## Insights Based on Outputs & Visualizations

* Moving averages (7-day & 30-day) highlight trend stability and price momentum.

* Correlation heatmap confirms strong relationships between lag features and price movement.

### Actual vs Forecast Plot shows that:

* ARIMA and SARIMA capture trend but struggle with volatility.

* LSTM closely follows actual price patterns, showing superior adaptability.

* Metric comparison proves LSTM has the lowest RMSE/MAE/MAPE, indicating highest accuracy.

## Conclusion

This internship project successfully demonstrates the development of a full stock forecasting pipeline using both classical and deep learning models.
Key conclusions:

* LSTM performs best due to its ability to learn nonlinear sequential patterns.

* Statistical models serve as strong baselines but lack dynamic learning capability.

The implemented workflow is scalable and can be expanded to multi-stock forecasting, sentiment-based prediction, or multi-feature modeling.
