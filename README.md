# Nonlinear Factor Models in Financial Markets: A Comparative Study of Autoencoders and PCA

This project explores the use of autoencoders as a nonlinear alternative to Principal Component Analysis (PCA) for dimensionality reduction, clustering, and anomaly detection in financial return data. Using historical data from Yahoo Finance, Alpha Vantage, and Polygon.io, we evaluate how effectively these models extract latent market factors and uncover nonlinear structures.

## Core Objectives
- Compare PCA and autoencoders for reconstructing standardized daily returns
- Evaluate performance using R² and Mean Squared Error (MSE)
- Apply K-Means clustering to latent features extracted by both models
- Detect anomalies using both traditional methods (Z-score, IQR) and machine learning (Isolation Forest)

## Datasets Used
- S&P 500 index returns (2000–2025) from Yahoo Finance
- NASDAQ Composite returns from Polygon.io
- Daily returns for major tech stocks (e.g., META, AAPL, TSLA) from Alpha Vantage API (`TIME_SERIES_DAILY`)

## Key Findings
- PCA consistently outperformed autoencoders in reconstructing returns, especially for volatile assets.
- However, clustering on autoencoder-derived latent features uncovered subtler relationships between assets that PCA missed.
- Isolation Forests provided more flexible and adaptive anomaly detection compared to traditional univariate methods like Z-score and IQR.

## Report
The full project report is written in LaTeX and available in `report.pdf`. It includes methodology, results, figures, and citations.

## Citation
If you found this project useful, feel free to cite or reference this GitHub repository directly.
