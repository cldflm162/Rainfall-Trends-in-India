# Rainfall Trends in India

## Overview

This project analyzes long-term rainfall trends, seasonal patterns, and anomalies in India. Using historical data from 1901 to 2015, it identifies key trends, anomalies, and patterns, and provides forecasts for future rainfall using advanced time series models.

## Goals

1. Uncover long-term trends and seasonal rainfall patterns.

2. Detect extreme years with significant deviations in rainfall.

3. Analyze the relationship between seasonal and annual rainfall.

4. Forecast future rainfall trends to aid in climate adaptation strategies.

## Dataset

The dataset contains historical rainfall data for India from 1901 to 2015. Each row represents a year, and the columns include:

YEAR: Year of observation.

JAN to DEC: Monthly rainfall values (in mm).

ANNUAL: Total annual rainfall (in mm).

Seasonal Aggregates: Rainfall for Jan-Feb, Mar-May, Jun-Sep, and Oct-Dec.

## Key Analyses

1. Annual Rainfall Trends

Plots show significant variability in annual rainfall with no clear long-term trend.

Peaks and troughs highlight years of extreme rainfall or drought.

2. Monthly and Seasonal Patterns

Monsoon months (June to September) dominate rainfall contributions.

Bar charts reveal July and August as the rainiest months, while others fall below the mean.

3. Climate Change Impact

A 10-year rolling average shows a slight decline in rainfall since 1960.

Early 20th century recorded higher averages compared to recent decades.

4. Anomaly Detection

Identified anomalous years with extreme rainfall or drought using statistical thresholds and Isolation Forest algorithm.

Visualization of anomalies highlights their distribution and seasonal dependencies.

5. Correlation Analysis

Moderate correlation between monsoon rainfall and October-December post-monsoon season.

Weak correlations for other seasons, indicating monsoonal independence.

6. Clustering Analysis

Using K-means clustering, years were categorized as "Dry," "Normal," or "Wet."

Results suggest a shift toward more dry years in recent decades.

7. Forecasting

Prophet model forecasts slight declines in rainfall with continued variability.

Highlights the importance of adaptive water resource strategies.

## Tools & Technologies

Python Libraries: Pandas, Plotly, Scikit-learn, Prophet.

Visualization: Interactive graphs for trend analysis and anomaly detection.

Statistical Models: Pearson correlation, Isolation Forest, and K-means clustering.

Forecasting: Prophet time-series model for future projections.

## Outputs:

Interactive visualizations of rainfall trends and anomalies.

Forecast plots with confidence intervals.

## Results & Findings

Rainfall Variability:

Significant annual variability with an overall slight decline.

Seasonal Dominance:

Monsoons are critical, contributing around 890 mm annually.

Anomalies:

Extreme years showcase the unpredictable nature of India’s rainfall.

Future Trends:

Predictions indicate a need for long-term water resource planning.


## Contributors:
Nikhil E S - cldflm162
