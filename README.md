# stockLstm

## Project Title

Stock Price Prediction using LSTM

## Description

This project uses LSTM (Long Short-Term Memory) neural networks to predict the future closing prices of a stock based on historical data. It utilizes the Keras library for building and training the LSTM model. The project fetches historical stock data from Yahoo Finance using the yfinance and pandas_datareader libraries. The data is preprocessed and scaled using MinMaxScaler from the scikit-learn library. The LSTM model is built and trained using the Sequential model from Keras, with various architectures and configurations explored.

The project includes the following steps:

1. Data Retrieval: Fetch historical stock data from Yahoo Finance.
2. Data Preprocessing: Clean the data and extract the desired features.
3. Data Scaling: Normalize the data using MinMaxScaler.
4. Data Preparation: Split the data into training and testing sets and create sequences of input and output data.
5. LSTM Model Building: Create and train the LSTM model using the Sequential model from Keras.
6. Prediction: Make predictions on the test data and evaluate the model's performance.
7. Visualization: Plot the actual and predicted prices to visualize the results.

The code is written in Python and utilizes various libraries such as pandas, numpy, matplotlib, mplfinance, and Keras.

## Installation

To run this project, you need to install the following dependencies:

- mplfinance: `!pip install mplfinance`
- libarchive: `!pip install libarchive`
- pandas: `!pip install pandas`
- yfinance: `!pip install yfinance`
- numpy: `!pip install numpy`
- matplotlib: `!pip install matplotlib`
- scikit-learn: `!pip install scikit-learn`
- Keras: `!pip install keras`

## Usage

1. Clone the repository: `git clone <repository_url>`
2. Install the required dependencies.
3. Open the Jupyter Notebook or Python script containing the code.
4. Modify the code if necessary (e.g., change the stock symbol, date range, model architecture).
5. Run the code and observe the results.
6. Experiment with different configurations and architectures to improve the model's performance.

Note: Make sure you have a working Python environment with the required libraries installed before running the code.

## License

This project is licensed under the [MIT License](LICENSE).
