# Financial Stocks Quantitative Analysis
## Overview

This project performs quantitative analysis on a group of financial stocks using Python's pandas and Plotly libraries. The project reads stock data from a CSV file, processes the data, and generates interactive visualizations to help understand stock performance and trends.
## Features

* Load and preprocess stock data from a CSV file
* Perform quantitative analysis including calculating returns, moving averages, and volatility
* Visualize stock performance and trends using interactive charts with Plotly
* Compare multiple stocks and analyze their historical performance

## Prerequisites

* Python 3.7 or higher
* pip (Python package installer)

## Installation

1. Clone the repository:

        git clone https://github.com/yourusername/Quant_stock_analysis.git

2. Navigate to the project directory:

        cd Quant_stock_analysis

3. Create a virtual environment (optional but recommended):

        python -m venv venv

4. Activate the virtual environment:

        Windows: venv\Scripts\activate

        MacOS/Linux: source venv/bin/activate

5. Install the required packages:

        pip install -r requirements.txt

## Data

* CSV File: The project expects a CSV file with stock data. Ensure the CSV file contains columns such as Date, Ticker, Open, High, Low, Close, Volume. The file should be named stocks_data.csv and placed in the data directory.

## Results

* Quantitative Analysis: Metrics such as daily returns, moving averages, and volatility are computed.
* Interactive Visualizations: Interactive charts showing stock prices, moving averages, and other relevant metrics.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
## Acknowledgments

* Pandas for data manipulation and analysis.
* Plotly for interactive visualizations.
