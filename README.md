# US Equity Market Analysis
### As it relates to each Presidency

---

The US Equity Market Analysis project is designed to provide insights into the performance of the US equity market during different presidential terms. The US equity market is a key indicator of the country's economic health, and many people believe that the policies and actions of the US government, particularly the president, can have a significant impact on the market. The project downloads market data for a pre-defined list of tickers, including popular indices such as the S&P 500, Dow Jones Industrial Average, NASDAQ, and Russell 2000, as well as the US dollar.

The project then creates separate dataframes for each US president's term in office, allowing for easy analysis of the market performance during each presidency. This can help to identify trends and patterns in the market and understand the impact of different presidents' policies on the economy.

The project is intended for use by anyone interested in analyzing the US market's historical performance, including investors, analysts, and researchers. The code is open-source and can be easily modified to analyze additional tickers or to customize the date ranges for each presidency.

The following sections provide information on how to install and use the project, including the required packages and how to customize the ticker list and presidential term dates.

---

## Data Source

The project uses Yahoo Finance API to download equity market data for the selected tickers. Yahoo Finance is a popular financial news and data platform that provides real-time market data, news, and analysis for stocks, indices, commodities, currencies, and cryptocurrencies. The API allows users to retrieve historical data for a specific ticker, including the open, high, low, close, and volume of each trading day.

---

## Installation

To run this project, you will need to install the following packages:

- yfinance

- pandas

- matplotlib

- seaborn

You can install these packages by running the following command:

    pip install yfinance pandas matplotlib seaborn

---

## Methodology

The project uses Python programming language and several data analysis packages, including Pandas, Matplotlib, and Seaborn. Pandas is a popular data manipulation library that provides data structures and functions to efficiently process and analyze large datasets. Matplotlib is a widely used data visualization library that provides functions to create various types of plots, including line plots, bar plots, scatter plots, and histograms. Seaborn is a higher-level data visualization library that provides a more aesthetically pleasing and informative visual representation of data.

The project follows the following methodology:

- Define a list of tickers to analyze and a dictionary of US presidents and their term dates.

- Download the historical stock market data for each ticker using the Yahoo Finance API.

- Preprocess the data by grouping the data by presidential terms.

- Calculate various statistics for each presidential term, including mean returns and correlation with other tickers.

- Visualize the data using various plots, including line plots, bar plots, and heatmaps, to identify trends and patterns in the equity market during different presidential terms.

---

## Usage

To use this project, simply run script. This will download the equity market data and create separate dataframes for each US president's term in office.

To customize the list of tickers to analyze, simply modify the ticker_list variable at the beginning of the script.

To customize the list of US presidents and their term dates, modify the presidencies dictionary at the beginning of the script.

To plot the stock market data for each presidency, run the script. This will create a separate plot for each ticker, with each presidency highlighted in a different color.

---

## Conclusion

The US Equity Market Analysis project provides a comprehensive and accessible tool to analyze the historical performance of the US equity market during different presidencies.

The analysis provides a detailed insight into the correlation and performance of five major US stock market indices and the US dollar from January 1971 to May 2023.

The correlation analysis is performed by slicing the original dataframe into separate dataframes for each US President's term in office. The correlation matrix between the stocks is calculated for each term, and a heatmap is created to visualize the correlation between the stocks. The correlation analysis provides information on how closely the stock market indices and the US dollar are related, which is useful for investors looking to diversify their portfolios.

The descriptive statistics are also calculated for each term in office, providing a summary of the performance of the stock market indices and the US dollar during each presidency. The statistics give insight into the volatility and average returns of the stocks and currency during each term, which is useful for investors looking to make informed investment decisions.

Overall, the analysis provides a comprehensive overview of the performance and correlation of the US stock market indices and the US dollar over the past five decades.
