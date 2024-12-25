# Financial Crime Detection using Anomaly Detection
This project demonstrates anomaly detection techniques for detecting financial crimes (e.g., fraud) using synthetic time series data. 
The goal is to identify fraudulent transactions by detecting anomalies in the transaction amounts using various methods including Isolation Forest, Z-Score, and Local Outlier Factor (LOF), One-Class SVM, and DBSCAN, along with seasonal decomposition for anomaly detection.
It also explores temporal trends and impacts of anomalies on business metrics.
# Overview of Steps
## Data Generation: Synthetic time series data is generated with added anomalies.
## Visualization: The time series with anomalies is visualized for reference.
# Anomaly Detection:
## Isolation Forest: Detects anomalies in the time series by training a model on standardized data.
## Z-Score: Detects outliers by comparing how far each transaction deviates from the mean.
## Local Outlier Factor (LOF): Identifies anomalies based on local density variation.
## Seasonal Decomposition: Decomposes the time series into trend, seasonal, and residual components; detects anomalies in residuals.
## One-Class SVM: A model trained on the data to identify anomalies using an RBF kernel.
## DBSCAN: Detects anomalies based on the density of data points in the time series.
# Visualization:
Visualizes the original transaction data along with detected anomalies.
Compares anomalies detected by each model.
# Results
## Time Series Visualization: Displays the original time series with highlighted anomalies.
## Model Comparison: Visualizes anomalies detected by Isolation Forest, One-Class SVM, Local Outlier Factor (LOF), and DBSCAN, alongside true anomalies.
