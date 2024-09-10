# Stock Visualization Dash App

## Overview

The Stock Visualization Dash App is an interactive web application designed to visualize and compare stock market data using Dash and Plotly. The app fetches real-time stock data from Yahoo Finance and provides users with candlestick charts and line plots to analyze various financial indicators.

## Features

- **Candlestick Charts**: Visualize detailed candlestick charts for selected stocks, showing open, high, low, and close daily prices on a hour-by-hour basis. This allows users to understand market trends and fluctuations over the day.

- **Indicator Comparison**: Compare different financial indicators such as Open, High, Low, Close, Adjusted Close, and Volume for multiple stocks. This feature helps users analyze and compare the performance of various stocks against each other.

- **Interactive UI**: The user interface includes:
  - A dropdown menu for selecting one or more stocks from a predefined list.
  - Radio buttons to choose the financial indicator for comparison.
  - A submit button to update the visualizations based on user selections.

- **Dynamic Updates**: The app dynamically generates charts and plots based on user inputs. Users can interactively select stocks and indicators, and view updated charts without reloading the page.

## Project Structure

The project directory is organized as follows:

- **`stocks.ipynb`**: Jupyter notebook containing the code for creating and running the Dash application. This script includes:
  - Fetching real-time stock data using the `yfinance` library.
  - Creating and displaying candlestick charts with Plotly.
  - Setting up the Dash app layout with dropdowns, radio buttons, and graphs.
  - Handling user interactions and updating the visualizations.

- **`company_tickers.json`**: JSON file that provides a list of stock tickers and their corresponding titles. This file is used to populate the dropdown menu in the Dash app with available stock options.

## Installation and Setup

1. **Clone the Repository**:
   Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/your-repository.git
   cd your-repository
   ```

2. **Install Dependencies**:
   Install the required Python libraries using pip:

   ```bash
   pip install yfinance plotly dash pandas
   ```

3. **Prepare Data**:
   Ensure that the `company_tickers.json` file is present in the project directory. This file should contain the stock tickers and their titles.

4. **Run the App**:
   Start the Dash app by running the Jupyter notebook:

   ```bash
   jupyter notebook stocks.ipynb
   ```

   Open the `stocks.ipynb` notebook in Jupyter and run the cells to launch the Dash app.

## Usage

1. **Select Stocks**:
   Use the dropdown menu in the app to choose one or more stocks from the list provided.

2. **Choose Indicator**:
   Select the financial indicator you want to analyze from the radio buttons.

3. **Submit**:
   Click the 'Submit' button to generate and display the candlestick charts and comparison plots for the selected stocks and indicator.

## Data Source

- **Stock Data**: Data is retrieved from Yahoo Finance using the `yfinance` library.
- **Ticker Symbols**: Stock tickers are provided in the `company_tickers.json` file.


## Acknowledgments

- [Yahoo Finance](https://finance.yahoo.com) for providing stock market data.
- [Plotly](https://plotly.com) for the interactive charting library.
- [Dash](https://dash.plotly.com) for creating the web application interface.
- [Bootstrap](https://getbootstrap.com) for styling the app interface.
```
