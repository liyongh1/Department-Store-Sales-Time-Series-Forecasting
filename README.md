# Department Store Sales Time-Series Forecasting

- Designed data preprocessing pipeline to join, clean, and aggregate about 420,000 samples of sales data from Kaggle using Spark SQL. Prepared data into coherent time-series format;

- Established pipeline for time-series seasonality differencing, feature engineering, dense vectorization using customized helper functions and Spark ML packages in Scala on Databricks;

- Developed stochastic SMA model, validated and tuned multiple ML models (such as RF, LR, GBT) using rolling k-fold CV. GBT achieved best SMAPE scores of less than 5% with a 1-day prediction window.
