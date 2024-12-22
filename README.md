# NASDAQ Daily Change Prediction

This project aims to build a Machine Learning model to predict the daily percentage change of the NASDAQ index. The model will be trained using a dataset created from various data sources, including historical NASDAQ data, the VIX index, and technical indicators calculated from this data. We might also explore web scraping to collect more data.

## Project Goals

- Predict the daily percentage change of the NASDAQ.
- Use historical NASDAQ data and the VIX index.
- Calculate and add technical indicators like RSI, MACD, and moving averages.
- Explore the possibility of web scraping to gather additional relevant data.

## Data Sources

The data for the model will come from several sources:

- **Historical NASDAQ Data**: Daily performance data of the NASDAQ index.
- **VIX Index**: A measure of market volatility.
- **Technical Indicators**: Calculated indicators like RSI, moving averages, derived from the NASDAQ historical data.
- **Web Scraping (optional)**: Collecting additional data from relevant financial websites.

## Approach

1. **Data Preprocessing**: Clean and transform the collected data so it's ready for Machine Learning.
2. **Modeling**: Build and train Machine Learning models, such as linear regression, decision trees, or neural networks.
3. **Model Evaluation**: Assess the model’s accuracy and reliability using metrics like RMSE and R^2.
4. **Prediction**: Use the trained model to predict the daily percentage change of the NASDAQ.

## Requirements

- Libraries: pandas, numpy, scikit-learn, matplotlib, yfinance and other dependencies for data processing and modeling.

## Installation

Clone this repo:
   ```bash
   git clone https://github.com/pbuitragoa33/NASDAQ-Change-Prediction.git

