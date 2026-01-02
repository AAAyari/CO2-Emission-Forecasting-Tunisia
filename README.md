# Academic Project: Forecasting Tunisia Daily Carbon Intensity

## Project Overview

This academic project focuses on time series forecasting of Tunisia’s daily carbon intensity using historical data spanning multiple years. The objective is to analyze temporal patterns in carbon intensity and build forecasting models capable of predicting future daily values.

The project is implemented entirely in Python using a Jupyter Notebook and is based on real daily carbon intensity data collected for Tunisia over four consecutive years.

---

## Datasets Used

The project relies on the following datasets:

* TN_2021_daily.csv
* TN_2022_daily.csv
* TN_2023_daily.csv
* TN_2024_daily.csv

Each dataset contains daily observations of carbon intensity in Tunisia. The files are combined and processed to form a continuous time series suitable for analysis and forecasting.

---

## Project Objectives

The main objectives of this project are to:

* Analyze daily carbon intensity trends in Tunisia
* Identify temporal patterns such as trends and seasonality
* Prepare multi-year time series data for forecasting
* Apply statistical forecasting models to daily data
* Evaluate forecasting performance using quantitative metrics

---

## Data Preparation and Processing

The notebook includes several preprocessing steps, including:

* Loading and merging multiple yearly datasets
* Converting date columns into a proper time index
* Ensuring chronological consistency of observations
* Handling missing or irregular values if present
* Structuring the data as a univariate daily time series

These steps ensure the data is suitable for reliable time series modeling.

---

## Exploratory Time Series Analysis

Exploratory analysis is conducted to understand the behavior of carbon intensity over time. This includes:

* Visualization of daily carbon intensity trends
* Identification of long-term movements
* Inspection of seasonal or cyclical patterns
* Initial assessment of stationarity

The insights gained from this phase guide the selection of forecasting models.

---

## Forecasting Methodology

The project applies time series forecasting techniques appropriate for daily environmental data. The workflow includes:

* Splitting the data into training and testing periods
* Selecting suitable forecasting models based on data characteristics
* Training models on historical daily observations
* Generating forecasts for future time steps
* Comparing predicted values with observed data

Residual analysis is also used to assess model adequacy.

---

## Model Evaluation

Forecast performance is evaluated using standard error metrics such as:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

These metrics quantify the accuracy of daily carbon intensity predictions and support model comparison.

---

## Tools and Technologies

* Python programming language
* Jupyter Notebook
* Pandas for time series manipulation
* NumPy for numerical operations
* Matplotlib and Seaborn for visualization
* Statsmodels and Scikit-learn for forecasting and evaluation

---

## Academic Value

This project demonstrates:

* Practical application of time series forecasting techniques
* Handling and merging of multi-year daily datasets
* Environmental data analysis in a national context
* Evaluation of forecasting models using residual diagnostics
* Application of predictive analytics to sustainability-related data

---

## Limitations

* Forecast accuracy depends on historical patterns remaining stable
* External factors affecting carbon intensity are not explicitly modeled
* The project is conducted in an academic, non-production context

---

## Conclusion

This project provides a structured and applied approach to forecasting daily carbon intensity in Tunisia. By leveraging multi-year historical data and established time series techniques, it highlights the role of forecasting in environmental analysis and decision support.
