# Stock Price Prediction Dashboard

## Overview
A real-time stock price prediction dashboard built with Dash and Python, featuring machine learning-based price forecasting using Support Vector Regression (SVR). This application allows users to visualize stock price trends and get predictions for future stock prices.

## Features
- Real-time stock data fetching using Yahoo Finance API
- Interactive stock price visualization
- Exponential Moving Average (EMA) analysis
- Price prediction using SVR (Support Vector Regression)
- Responsive web interface
- Dynamic date range selection
- Multiple stock symbol support

## Tech Stack
- **Frontend**: Dash, HTML, CSS
- **Backend**: Flask, Python
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn
- **Data Visualization**: Plotly
- **Stock Data**: yfinance

## Prerequisites
- Python 3.8+
- pip package manager

## Installation

1. Clone the repository:
```bash
git clone https://github.com/dhanjitk16/StockPrediction.git
cd StockPrediction
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Start the application:
```bash
python app.py
```

2. Open your web browser and navigate to `http://localhost:8050`

3. Enter a stock symbol (e.g., AAPL for Apple Inc.) and select the desired prediction timeframe

## Features in Detail

### Stock Price Visualization
- View historical closing and opening prices
- Interactive date range selection

### Technical Analysis
- Exponential Moving Average (EMA) calculation
- Price trend analysis

### Price Prediction
- Machine learning-based price forecasting
- Support Vector Regression model

## Project Structure
```
stock-prediction-dash-master/
├── app.py              # Main application file
├── model.py           # ML model implementation
├── requirements.txt   # Project dependencies
├── vercel.json       # Vercel deployment configuration
└── assets/          # Static assets
    ├── stocks-img.jpg
    └── styles.css
```


## Author
- [dhanjitk16](https://github.com/dhanjitk16)
