# S-P-500-Comparison-Project

# Stock Market Performance Analysis

This project analyzes the performance of Apple, Google, Microsoft, and Amazon stock compared to the S&P 500 index from 2014 to 2024.

## Project Goals

*   Compare the cumulative returns of individual tech stocks to the S&P 500.
*   Analyze the volatility of individual stocks compared to the broader market.
*   Visualize the data using Matplotlib and Tableau.

## Data Source

*   Yahoo Finance API (`yfinance` library in Python)

## Tools Used

*   Python
*   Jupyter Notebook
*   Pandas
*   Matplotlib
*   Tableau

## Files

*   `stock\_analysis.ipynb`: Jupyter Notebook containing the Python code for data analysis and visualization.
*   `stock\_data.xlsx`: Excel file containing the following sheets:
    *   `Adjusted\_Close`: Adjusted closing prices of the stocks and the S&P 500.
    *   `Dollar\_Gains`: Dollar gains (or losses) for each asset.
    *   `Cumulative\_Returns`: Cumulative percentage returns for each asset.
*   `README.md`: This file.

## Analysis

The analysis includes:

*   Downloading historical stock data using the `yfinance` library.
*   Calculating cumulative returns and dollar gains.
*   Visualizing the cumulative returns using Matplotlib.
*   Creating interactive visualizations in Tableau to compare performance and volatility.

## Running the Code

1.  Make sure you have the required libraries installed (`yfinance`, `pandas`, `matplotlib`).
2.  Open the `stock\_analysis.ipynb` notebook in Jupyter.
3.  Run the cells in the notebook to download the data, perform calculations, and generate visualizations.

## Visualizations

The project includes visualizations created with Matplotlib and Tableau to show:

*   Cumulative returns of each stock compared to the S&P 500.
*   Dollar gains of each stock.
*   Volatility analysis using box plots and other techniques (in Tableau).

## Conclusion

This project provides insights into the performance and volatility of major tech stocks compared to the broader market. The analysis can be extended to include other metrics, time periods, and stocks to gain a deeper understanding of investment trends and risks.
