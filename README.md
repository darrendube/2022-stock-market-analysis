# 2022 US Stock Market Analysis
![](https://img.shields.io/badge/license-MIT-blue)

In this Jupyter Notebook, I investigate how the various sectors of the US economy performed on the stock market in 2022 by creating a market cap-weighted index of each sector, and plotting its returns over the year.

The stocks are classified into sectors according to the Global Industry Classification Standard (GICS):
 - Communication Services
 - Consumer Discretionary
 - Consumer Staples
 - Energy
 - Financials
 - Healthcare
 - Industrials
 - Information Technology
 - Materials
 - Real Estate
 - Utilities

# How to use

The analysis was done in a Jupyter Notebook. This analysis can be viewed by opening the notebook, but to run it again, you'll need
 - a dev environment that can run Jupyter Notebooks (e.g. through a VS Code extension, or by installing [conda](https://github.com/conda/conda)
 - the following libraries:
   - [`yfinance`](https://pypi.org/project/yfinance/) - a library that enables downloading of price data from Yahoo! Finance
   - `numpy`
   - `pandas`
   - `matplotlib`
     
The sixth code block involves downloading the price data of about **5000 stocks**, and may therefore take a while.
