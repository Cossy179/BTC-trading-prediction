# BTC Price Prediction using LSTM

This project demonstrates how to predict Bitcoin (BTC) prices using a Long Short-Term Memory (LSTM) neural network. The model is trained on historical BTC price data and can be used to forecast future price movements.

## Requirements

* Python 3.6 or higher
* TensorFlow 2.0 or higher
* Keras
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* ccxt

To install the necessary libraries, run:
```
bash pip install tensorflow keras pandas numpy scikit-learn matplotlib ccxt
```
## Data

The project uses historical BTC price data from Yahoo Finance. The data is loaded into a Pandas DataFrame and preprocessed before being fed into the LSTM model.

## Model

The LSTM model consists of two LSTM layers followed by two Dense layers. The model is trained using the Adam optimizer and the mean squared error loss function.

## Usage

1. Clone the repository.
2. Install the required libraries.
3. Run the `BTC_price_prediction.ipynb` notebook.

The notebook contains the code for loading the data, preprocessing it, training the model, and evaluating its performance.

## Results

The model achieves a good accuracy on the test dataset. The predicted prices closely follow the actual prices.

## Disclaimer

This project is for educational purposes only and should not be considered as financial advice.
