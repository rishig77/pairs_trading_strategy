Pairs_Trading_Strategy

**Project Title:** Pairs Trading with Coca-Cola and PepsiCo Stocks in Python

**Project Description:** This project explores pairs trading, a market-neutral strategy, using Coca-Cola (KO) and PepsiCo (PEP) stocks as an example. It analyzes the historical price relationship between these two assets to identify profitable trading opportunities when their prices diverge. The project compares the performance of this statistical arbitrage strategy with a traditional 50/50 buy-and-hold approach.

**My Approach:**

* Data Retrieval: Retrieves historical stock price data for KO and PEP from Yahoo Finance using the `requests` library.
* Data Analysis: Analyzes the correlation and cointegration between KO and PEP prices to identify their historical relationship.
* Pairs Trading Strategy: Implements a pairs trading strategy that generates buy and sell signals based on divergences from the historical price relationship.
* Performance Comparison: Compares the returns and risk of the pairs trading strategy with a 50/50 buy-and-hold portfolio of KO and PEP.

**Key Tools and Technologies:**

* Python libraries: `yfinance`, `requests`, `numpy`, `pandas`, `matplotlib`
* Data Source: Yahoo Finance
* Stocks: Coca-Cola (KO), PepsiCo (PEP)

**Impact:** This project provides a practical example of how to implement a pairs trading strategy in Python. It demonstrates the potential of statistical arbitrage and offers insights into the benefits and challenges associated with this approach.
