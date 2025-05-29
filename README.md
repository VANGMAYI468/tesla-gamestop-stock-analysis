# Tesla and GameStop Stock Data Analysis (2010–2020)

This project downloads, processes, and visualizes stock market data for **Tesla (TSLA)** and **GameStop (GME)** from 2010 to 2020 using the `yfinance` library. It also scrapes and displays GameStop's historical revenue data from MacroTrends.

## 📁 Contents

- Tesla stock data download and display
- GameStop stock data download and CSV export
- GameStop revenue data scraped from MacroTrends
- Data visualization using Matplotlib

## 📊 What the Code Does

1. **Download Stock Data**  
   - Uses `yfinance` to get daily stock prices for TSLA and GME from 2010 to 2020.
   - Resets the index so the `Date` column is available for plotting.

2. **Preview Data**  
   - Prints the first and last five rows of stock data.

3. **Scrape Revenue Data**  
   - Sends a web request to MacroTrends and parses GameStop's quarterly revenue using `pandas.read_html`.

4. **Visualize Stock Prices**  
   - Plots the closing prices of Tesla and GameStop stock over time using Matplotlib.

## 🛠 Requirements

Install the necessary Python packages (if not already installed):

```bash
pip install yfinance pandas matplotlib requests
