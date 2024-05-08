# Stock Trend Prediction App

## Overview
This Stock Trend Prediction app is designed to forecast stock prices using a machine learning model built with Keras. The app uses Streamlit for an interactive web interface, allowing users to enter a stock ticker and view the predicted trends alongside historical price data. The project includes a pre-trained LSTM model and a Jupyter notebook that details the model's training process.

## Features
- **Interactive Stock Ticker Input**: Users can input any stock ticker available on Yahoo Finance.
- **Historical Data Visualization**: Displays stock price data from 2010 to 2023.
- **Price Prediction**: Showcases the model's prediction of future stock prices.
- **Moving Averages**: Plots 100-day and 200-day moving averages for trend analysis.

## Installation

To run this project, you will need Python installed on your system, along with several libraries including TensorFlow, Pandas, NumPy, Matplotlib, and Streamlit.

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd <repository-name>
2. **Install Required Libraries
   pip install -r requirements.txt
3. **Run the Steamlit App**
   streamlit run app.py
## Files
- `app.py`: The main Streamlit application script that provides the web interface.
- `keras_model.h5`: The pre-trained LSTM model used for making predictions.
- `LSTM Model.ipynb`: A Jupyter notebook detailing the process of training the LSTM model.

## Usage
Once the application is running, navigate to `http://localhost:8501` in your web browser. Enter a stock ticker in the input field, and the app will display the historical data and predictions.

## How it Works
- The app uses `yfinance` to fetch historical stock data based on user input.
- It then processes this data to align with the training format of the LSTM model.
- The model predicts future stock prices, which are then displayed alongside actual historical prices in the app.

## Contributing
Contributions to this project are welcome. You can contribute in several ways:
- Enhancing the model's accuracy or efficiency.
- Adding new features to the Streamlit application.
- Improving the user interface.

## License
Include a license here, typically this project would be licensed under the MIT License. 
