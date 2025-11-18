# NASDAQ Daily Change Prediction 

This project aims to build a Machine Learning model to predict the daily percentage change of the NASDAQ index. The model will be trained using a dataset created from various data sources, including historical NASDAQ data, the VIX index, and technical indicators calculated from this data.

Here is a graphic summary of the project execution:

![Imagen1](./Related%20Images/Page1.png)
![Imagen2](./Related%20Images/Page2.png)
![Imagen3](./Related%20Images/Page3.png)
![Imagen4](./Related%20Images/Page4.png)
![Imagen5](./Related%20Images/Page5.png)
![Imagen6](./Related%20Images/Page6.png)

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
- **FRED**: Specifically daily frequency data from the Federal Reserve St. Louis.
- **Others sources via APIs**: Sites like Alpha Vantage.
- **Web Scraping (optional)**: Collecting additional data from relevant financial websites. 

## Approach

1. **Data Preprocessing**: Clean and transform the collected data so it's ready for Machine Learning.
2. **Modeling**: Build and train Machine Learning models, such as NN, Gradient, RF, DNN.
3. **Model Evaluation**: Assess the model’s accuracy and reliability using various metrics.

## Requirements

- Libraries: pandas, numpy, scikit-learn, matplotlib, keras, yfinance and other dependencies for data processing and modeling.

## Installation

Clone this repo:
   ```bash
   git clone https://github.com/pbuitragoa33/NASDAQ-Change-Prediction.git

