# Bitcoin Time Series Forecasting & Simulation

## Project Overview
This project explores various time series forecasting techniques applied to Bitcoin (BTC) price data. The primary objective is to develop accurate forecasting models and assess future price distributions using simulation techniques. This work can help traders, analysts, and researchers make informed decisions based on probabilistic forecasting rather than deterministic predictions.

## Key Features
- **Exploratory Data Analysis (EDA):** Visualizing BTC trends using candlestick charts, moving averages (SMA & EMA), and statistical summaries.
- **Statistical Forecasting Models:** Implementation of ARIMA, SARIMA, and SARIMAX to model BTC price trends.
- **Machine Learning Approach:** Facebook Prophet for trend detection and seasonal adjustments.
- **Monte Carlo Simulations:** Assessing future price distributions based on probabilistic modeling.
- **Cross-validation:** Evaluating model performance with multiple error metrics, including MAE, RMSE, and MAPE.
- **Potential Enhancements:** Incorporation of Google Trends data and deep learning models such as LSTM and Transformers.

## Methodology
1. **Data Preprocessing:** Cleaning and transforming historical BTC price data for model training.
2. **EDA & Feature Engineering:** Understanding price patterns through visualization and trend extraction.
3. **Forecasting Models:** Applying ARIMA, SARIMA, SARIMAX, and Prophet for future predictions.
4. **Simulation Techniques:** Monte Carlo simulations to estimate BTC price distributions.
5. **Model Evaluation:** Using cross-validation and error metrics (MAE, RMSE, MAPE) to assess forecast accuracy.

## Technologies Used
- **Python**: Pandas, NumPy, Scikit-learn, Statsmodels
- **Forecasting Libraries**: Facebook Prophet, ARIMA, SARIMA, SARIMAX
- **Visualization Tools**: Matplotlib, Seaborn, Plotly
- **Simulation & Validation**: Monte Carlo methods, Time Series Cross-Validation

## Results & Findings
- The Prophet model captured BTC's long-term trends effectively but showed some limitations in short-term volatility prediction.
- ARIMA-based models performed well for stationary data but struggled with seasonality.
- Monte Carlo simulations provided a probabilistic outlook, which is valuable for risk assessment.
- Cross-validation demonstrated varying accuracy depending on the model and time horizon.
- Deep Learning Models: Implementing LSTM and Transformer-based time series forecasting.

## Future Enhancements

- **Additional External Features:** Incorporating Google Trends data and on-chain BTC metrics.
- **Automated Model Selection:** Hyperparameter tuning using Bayesian optimization.

## How to Use
1. Clone the repository and install dependencies.
2. Load BTC price data (or any other asset data in the same format).
3. Train different models and compare their performance.
4. Run Monte Carlo simulations to assess future price risks.
5. Evaluate forecast accuracy using cross-validation.


This project serves as a comprehensive guide for time series forecasting in finance. I invite data scientists, traders, and researchers to explore the repository, test alternative models, and contribute enhancements!
