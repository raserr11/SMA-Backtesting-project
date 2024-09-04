# Simple Moving Average (SMA) Strategy Backtesting

## Project Overview
This project represents my first step towards applying data science to trading. It implements and backtests a Simple Moving Average (SMA) strategy on historical market data, serving as an initial exploration of the backtrader library. The primary goal is to familiarize myself with the tools and techniques involved, while evaluating the effectiveness of this basic strategy.

## Dataset
The dataset used in this project includes historical market data, specifically:
- **Asset**: The financial instrument being traded (e.g., stock, commodity).
- **Date**: The date of each observation.
- **Close Price**: The closing price of the asset on the given date.

The data is sourced from a CSV file, `GOLD_data.csv`, containing the necessary historical data for backtesting.

## Key Question

1. **How does the SMA strategy perform over the selected time period?**  
   The strategy's performance is evaluated based on final portfolio balance.

## Visualizations
The project includes various visualizations to analyze the strategy's performance:
- **Buy/Sell Signals**: Markers on the price chart to indicate where the strategy executed trades.
- **Moving Averages**: A plot showing the price along with the SMA to visualize the trading signals.

## Technologies Used
- **Python**: Core programming language for implementing the strategy and backtesting.
- **Backtrader**: Framework for backtesting the SMA strategy.
- **Pandas**: Data manipulation and processing.
- **Matplotlib**: Visualization of strategy performance and trade signals.

## Installation
To run this project, ensure you have Python installed and the required libraries:
```bash
pip install backtrader pandas matplotlib
```

## Additional Notes
- **Provisional Outputs**: Current outputs are generated using basic `print()` statements. A function is being developed to streamline and enhance the output formatting.
- **Customization**: The backtesting period can be customized by entering specific start and end dates.