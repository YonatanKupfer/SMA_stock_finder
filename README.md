# SMA Stock Finder

This repository contains a Python-based Jupyter Notebook that analyzes stock data to calculate and compare Simple Moving Averages (SMA) over various time frames. The tool identifies stocks closest to their SMAs and highlights those with the smallest difference between the 200-day and 50-day SMAs.

## Features

- **Data Analysis with SMA:** Calculates the 200-day, 150-day, 100-day, and 50-day SMAs for each stock in a portfolio.
- **Distance Calculation:** Computes the distance of each stock's current price from its respective SMA in both absolute and percentage terms.
- **Stock Sorting:** Sorts stocks by their proximity to SMAs to help identify opportunities.
- **Cross-SMA Analysis:** Highlights stocks with the smallest absolute difference between their 200-day and 50-day SMAs.

## Files

1. **`sma_notebook.ipynb`**: The Jupyter Notebook that performs the SMA calculations and analysis.
2. **`portfolio.csv`**: A CSV file containing the list of stock symbols for analysis.
3. **`README.md`**: This file, describing the purpose, features, and usage of the repository.

## Requirements

- Python 3.x
- Required libraries:
  - `pandas`
  - `matplotlib`
  - `yfinance`
  - `datetime`

Install the required libraries using:

```bash
pip install pandas matplotlib yfinance
```
## Usage
1.	Clone the repository:
```bash
git clone https://github.com/YourUsername/SMA_stock_finder.git
```
2.	Navigate to the directory:
```bash
cd SMA_stock_finder
```
3.	Place your list of stock symbols in portfolio.csv under the column Symbol.
4.	Open the Jupyter Notebook sma_notebook.ipynb in your preferred IDE or environment:
```bash
jupyter notebook sma_notebook.ipynb
```
5.	Run the notebook cells to analyze the SMA data for the stocks in your portfolio.

## Output
•	The notebook outputs sorted dataframes showing stocks closest to their SMAs.
•	Identifies stocks with the smallest difference between their 200-day and 50-day SMAs.
•	Any unknown or invalid tickers are flagged for review.

## Contributing
Feel free to submit issues or pull requests to enhance functionality or fix bugs. Contributions are welcome!
