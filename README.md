# Stock Market Prediction

This repository contains a project for predicting stock prices using Long Short-Term Memory (LSTM) neural networks. The model is trained on historical stock price data and can be used to make predictions on future stock prices.

## Table of Contents

- [Overview](#overview)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Overview

The goal of this project is to demonstrate how LSTM neural networks can be used to predict stock prices based on historical data. The model is trained on a dataset containing stock prices for various companies over a period of five years.

## Dependencies

To run this project, you will need the following dependencies:

- Python (>=3.6)
- Pandas
- Matplotlib
- Numpy
- TensorFlow
- Scikit-Learn
- Seaborn

You can install the required dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Madhavyamjala/Stockmarketpredict.git
   cd Stockmarketpredict
   ```

2. **Download Data:**

   Download the historical stock price dataset (e.g., `all_stocks_5yr.csv`) and place it in the project directory.

3. **Run the Code:**

   Execute the Python script `stock_prediction.py` to train the LSTM model and make predictions. Make sure to update the file path if your data file has a different name.

   ```bash
   python stock_prediction.py
   ```

4. **View Results:**

   After running the script, the model will generate predictions for the test data. The results will be displayed in a matplotlib plot.

## Results

The model will generate predictions for the test data and compare them with the actual stock prices. The evaluation metrics (Mean Squared Error and Root Mean Squared Error) will also be printed to the console.

---

Feel free to reach out if you have any questions or suggestions!

*Note: Please make sure to replace `Madhavyamjala` with your actual GitHub username in the clone command.*
