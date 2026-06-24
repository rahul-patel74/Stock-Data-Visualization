# README for Revenue Data and Building a Dashboard.ipynb

## Project Overview
This notebook demonstrates the process of extracting and visualizing stock data for two prominent companies, Tesla (TSLA) and GameStop (GME). It utilizes Python libraries such as `yfinance` for fetching historical stock prices and `BeautifulSoup` for web scraping financial revenue data. The extracted data is then cleaned, processed, and visualized using `matplotlib` to display both stock prices and revenue trends.

## Contents

1.  **Setup and Libraries**: Installs necessary libraries (`yfinance`, `bs4`, `nbformat`, `matplotlib`) and imports `yfinance`, `pandas`, `requests`, and `BeautifulSoup`.
2.  **Warning Filter**: Includes code to ignore `FutureWarning` messages for cleaner output.
3.  **Graphing Function (`make_graph`)**: Defines a reusable function to plot historical stock prices and revenue data on a single graph. This function takes stock data, revenue data, and the stock symbol as input.
4.  **Question 1: Tesla Stock Data Extraction**: Uses `yfinance` to extract historical stock data for Tesla (TSLA) and displays the first five rows after resetting the index.
5.  **Question 2: Tesla Revenue Data Extraction**: Performs web scraping using `requests` and `BeautifulSoup` to extract Tesla's quarterly revenue data from a specified URL. The data is cleaned by removing commas and dollar signs and handling null/empty values, then the last five rows are displayed.
6.  **Question 3: GameStop Stock Data Extraction**: Similar to Question 1, extracts historical stock data for GameStop (GME) using `yfinance` and displays the first five rows.
7.  **Question 4: GameStop Revenue Data Extraction**: Similar to Question 2, web scrapes GameStop's quarterly revenue data, cleans it, and displays the last five rows.
8.  **Question 5: Plot Tesla Stock Graph**: Invokes the `make_graph` function to visualize Tesla's stock price and revenue data.
9.  **Question 6: Plot GameStop Stock Graph**: Invokes the `make_graph` function to visualize GameStop's stock price and revenue data.

## How to Use

1.  Run all cells in the notebook sequentially.
2.  Observe the output for extracted data and the generated graphs for Tesla and GameStop.
3.  Ensure you have an active internet connection for data extraction from `yfinance` and web scraping.

## Dependencies

*   `yfinance`
*   `pandas`
*   `requests`
*   `BeautifulSoup4`
*   `matplotlib`
*   `nbformat`

These libraries are installed at the beginning of the notebook.
