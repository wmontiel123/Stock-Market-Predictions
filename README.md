# Stock Market Price Prediction

This script aims to predict stock market prices using historical data. It utilizes various libraries and techniques to achieve the desired prediction.

## Prerequisites

Before running the script, make sure you have the following libraries installed:

- `pandas_datareader`: Used for fetching stock market data.
- `matplotlib`: Used for visualizing the data and predictions.
- `pandas`: Used for data manipulation and analysis.
- `datetime`: Used for working with dates and times.
- `urllib`: Used for making HTTP requests to fetch stock market data.
- `numpy`: Used for numerical operations.
- `tensorflow`: The code has been tested with TensorFlow 1.6. This library is used for building and training the prediction model.
- `sklearn`: Used for preprocessing data with the `MinMaxScaler` class.

You can install these libraries using `pip` with the following command:

```
pip install pandas_datareader matplotlib pandas datetime urllib3 numpy tensorflow scikit-learn
```

## Usage

To use this script, follow these steps:

1. Ensure that you have the required libraries installed.
2. Clone or download the script from the repository.
3. Open the script in your preferred Python editor or IDE.
4. Set the desired configuration parameters such as the stock symbol, prediction period, etc.
5. Run the script.

## Configuration

The script provides a few configuration parameters that can be adjusted based on your requirements:

- `stock_symbol`: The symbol or ticker of the stock you want to predict.
- `start_date`: The start date of the historical data.
- `end_date`: The end date of the historical data.
- `prediction_period`: The number of future days for which you want to make predictions.
- `train_test_split_ratio`: The ratio of the data used for training versus testing.
- `num_epochs`: The number of epochs for training the model.
- `batch_size`: The batch size used during training.

Adjust these parameters according to your needs to achieve the desired results.

## Results

The script will generate a graph showing the historical and predicted stock market prices for the specified stock symbol. You can analyze this graph to observe the accuracy of the predictions.

## Contributing

Contributions to this script are welcome. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This script is licensed under the [MIT License](LICENSE). Feel free to use and modify it according to the terms of the license.
