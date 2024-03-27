# COVID19-ARIMA-TimeseriesForecasting
COVID19-ARIMA-Forecasting uses ARIMA and alternative models to predict daily COVID-19 cases in US states from Jan 1 to Feb 10, 2021. It aims for accuracy in understanding pandemic trends, leveraging statistical analysis to inform decision-making.

# COVID19-ARIMA-Forecasting

## Overview
This project employs the ARIMA (AutoRegressive Integrated Moving Average) model, alongside alternative forecasting models, to predict daily COVID-19 cases across several US states. Utilizing historical data on COVID-19 incidences, the project aims to provide accurate forecasts from January 1st, 2021, through February 10th, 2021. This endeavor is not only a practical application of time series analysis but also contributes to the ongoing efforts in understanding and managing the COVID-19 pandemic impacts.

## Dataset
The dataset comprises daily COVID-19 cases from various US states throughout 2020. This comprehensive dataset serves as the foundation for training and testing the forecasting models developed in this project.

## Methodology
- **ARIMA Model**: The core of our analysis, the ARIMA model, is fine-tuned for each state's data to predict future cases effectively. The model's parameters (p, d, q) x (P, D, Q) were meticulously selected to best fit the time series data.
- **Alternative Models**: In addition to the ARIMA model, alternative forecasting methods, including the Holt-Winters model, were explored to ensure robustness and accuracy in our predictions.
- **Model Selection**: Forecasts were generated using the best-performing model and a subset of high-performing alternative models. Model selection was based on criteria such as AICC (Akaike Information Criterion Corrected) or BIC (Bayesian Information Criterion) weights.
- **Evaluation**: The models' performance was evaluated using the Mean Absolute Percentage Error (MAPE), with a lower MAPE indicating higher accuracy.

## Results
The project's outcome includes a daily forecast of COVID-19 cases for the designated period, across the assigned US states. These results are compiled in a single Excel spreadsheet, showcasing the predictive prowess of the developed models.

## Installation and Usage
The project's codebase is written in R, leveraging the statistical computing and graphics capabilities of the R environment. To replicate or extend this analysis:
1. Ensure you have R installed on your machine.
2. Clone this repository to your local machine.
3. Install required R packages using `install.packages("packageName")`.
4. Run the RMarkdown file `TimeseriesCodeARIMA.Rmd` to execute the analysis.


