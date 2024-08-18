# Anomaly Detection in New York Taxi Dataset

## Overview

This project focuses on detecting anomalies within the [New York Taxi Dataset](https://github.com/numenta/NAB/blob/master/data/realKnownCause/nyc_taxi.csv) to uncover valuable insights for decision-making. Key steps include:

- Identified various anomalies in the dataset, revealing patterns and insights.
- Assessed stationarity using KPSS, Dickey-Fuller, and Phillips-Perron tests.
- Fitted an ARMA model after confirming stationarity.
- Evaluated different ML models based on AIC and BIC criteria using ACF and Partial-ACF plots.

## Conclusion

The analysis revealed that all detected anomalies correspond to significant dates in U.S. and New York history, such as Independence Day, Thanksgiving, Christmas, New Year's Eve, and a massive snowstorm in January 2015.

Additionally, the data analysis uncovered that taxi demand peaks during weekday mornings, likely due to work commutes, while weekend demand surges around midnight, reflecting increased leisure activities. This insight is crucial for increasing the profit of the taxi services.
