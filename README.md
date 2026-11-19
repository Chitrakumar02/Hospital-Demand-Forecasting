# Hospital Demand Forecasting

## Project Overview

Hospital Demand Forecasting is a data analytics and machine learning project developed to analyse historical healthcare encounter data and predict future patient demand.

The project uses a synthetic healthcare dataset containing patient encounters from multiple anonymised healthcare organisations. The objective is to identify demand patterns, study historical trends and develop forecasting models that can support healthcare resource planning.

## Objectives

- Analyse historical healthcare encounter data.
- Aggregate patient visits into weekly time-series data.
- Identify trends, seasonal patterns and unusual demand fluctuations.
- Develop and compare forecasting models.
- Predict patient demand for the next 13 weeks.
- Prepare a resource planning table for staffing, beds and follow-up calls.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Statsmodels
- Prophet
- Jupyter Notebook

## Forecasting Models

The following models were explored:

1. Seasonal Naive Forecasting
2. SARIMA
3. Prophet
4. Random Forest Regression

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Weighted Absolute Percentage Error (WAPE)
- Rolling-origin backtesting

Random Forest achieved lower errors than Seasonal Naive in the rolling-origin comparison. However, the forecasting errors remained high, indicating that further improvements are required.

## Project Outputs

The project includes:

- Exploratory data analysis charts
- Forecast comparison charts
- Rolling-origin backtesting results
- 13-week demand forecast
- Prediction intervals
- Hospital resource planning table
- Detailed project report

## Dataset

The project uses a synthetic healthcare dataset obtained from Hugging Face:

george-essam-ai/synthea-healthcare-dataset

The dataset does not represent actual hospital records.

## Limitations

The dataset contains unusual demand fluctuations and ends in November 2021. Therefore, the generated forecasts are historical model outputs and should not be interpreted as current hospital demand predictions.

The resource planning estimates are illustrative assumptions rather than clinical staffing or bed-allocation standards.

## Conclusion

This project demonstrates the application of data analytics, time-series forecasting and machine learning techniques to healthcare demand analysis. It provides a foundation for understanding historical patient demand and exploring data-driven approaches to resource planning.