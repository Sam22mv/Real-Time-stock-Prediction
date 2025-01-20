# Real-Time-stock-Prediction

# Stock Price Prediction using Prophet

This project is a Python-based tool for predicting stock prices using historical data and the Facebook Prophet forecasting model. It fetches stock data from Yahoo Finance, prepares it for modeling, trains a Prophet model, and generates forecasts for future stock prices. The tool also evaluates the model's performance using Mean Absolute Error (MAE) and visualizes the predictions.

## Features
- **Fetch Historical Stock Data**: Automatically download historical stock data from Yahoo Finance.
- **Data Preparation**: Prepare the data for Prophet modeling by formatting the date and price columns.
- **Model Training**: Train a Prophet forecasting model on the stock data.
- **Stock Price Forecasting**: Predict future stock prices for a specified number of days.
- **Visualization**: Plot actual vs. predicted stock prices with confidence intervals.
- **Model Evaluation**: Calculate and display the Mean Absolute Error (MAE) of the predictions.
- **Command-line Interaction**: Input the stock symbol directly from the command line for ease of use.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/stock-price-prediction.git
    cd stock-price-prediction
    ```

2. **Install the required Python packages**:
    ```bash
    pip install -r requirements.txt
    ```

   Make sure the following libraries are installed:
   - `yfinance`
   - `pandas`
   - `matplotlib`
   - `prophet`
   - `scikit-learn`

3. **Run the application**:
    ```bash
    python stock_prediction.py
    ```

## Usage

1. Run the script and enter the stock symbol when prompted (e.g., AAPL, TSLA).
2. The script will fetch the historical stock data, train the Prophet model, and predict the next year's stock prices.
3. It will display the predicted closing prices, the Mean Absolute Error (MAE), and plots showing the forecast.

## Example

```bash
Enter the stock symbol (e.g., AAPL, TSLA, etc.): AAPL
