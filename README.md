# Project Title: Consumer Price Index (CPI) Forecasting

## Overview

This project involves forecasting the Consumer Price Index (CPI) using various statistical and machine learning models. The dataset contains quarterly CPI values from March 1997 to December 2021. The primary goal is to predict CPI values for the period from March 2022 to December 2023.

The project uses exploratory data analysis (EDA), time series modeling techniques (e.g., ARIMA, Exponential Smoothing), and evaluation metrics to identify the best model for accurate CPI prediction.

## Features

- Exploratory Data Analysis: Visualization of CPI trends and seasonality, statistical summaries, and decomposition of the CPI time series.

- Candidate Models Implementation: Baseline models (Random Walk) and advanced models (ARIMA, Exponential Smoothing) with hyperparameter tuning using AIC and BIC.

- Model Evaluation and Validation: Real-time validation with holdout data, MSE as the evaluation metric, and forecast intervals for uncertainty assessment.

- Results and Comparison: Detailed comparison of models based on performance and insights into why specific models were effective.

## Key Results

- Model Performance: The ARIMA(2,1,2) model achieved the lowest MSE.

- Insights: The models effectively captured the long-term trend and seasonality in the CPI data.

- Forecast: Predicted CPI values from March 2022 to December 2023 provide actionable insights for economic planning.
