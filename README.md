# Stock Price Prediction Using LSTM Networks

## Project Overview
This project involves predicting stock prices using Long Short-Term Memory (LSTM) networks. The model is designed to capture temporal patterns in historical stock data to forecast future prices.

## Key Features
- **LSTM Model Architecture**: Developed a 2-layer LSTM model using TensorFlow for accurate stock price prediction.
- **Hidden Units Configuration**: Implemented 64 hidden units per LSTM layer to enhance the model's ability to learn temporal trends.
- **Data Preprocessing**: Utilized MinMaxScaler to normalize the data, ensuring optimal input range for model training.
- **Performance Metrics**: Achieved a Root Mean Squared Error (RMSE) of 0.006 on test data, with optimization performed using the Adam optimizer for efficient training.

## Installation
Clone the repository and install the required dependencies:
```bash
git clone https://github.com/username/repository.git
cd repository
pip install -r requirements.txt
