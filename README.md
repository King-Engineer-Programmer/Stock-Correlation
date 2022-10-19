# Stock-Correlation

In this assignment, you will analyze the following five semiconductor stocks: HD, INTC, AMD, MU, NVDA, and TSM. Then, you will choose the stock with the least correlation to JNJ in order to diversify a portfolio. The data was generated using the GOOGLEFINANCE historical market data script.
To learn more about diversification and how correlation in a portfolio helps to minimize risk, review this article on diversification.

Instructions


Import the Pandas and Plotly Express libraries.


Read the CSV file into a DataFrame and set the date column as the index.


Use the pct_change function to calculate the daily returns.


Drop any rows with missing data.


Create a correlation matrix.


Create a heatmap using the correlation matrix.


Use the unstack function to find the best stock pair for diversification.


Based on the results, in a sentence, explain which semiconductor stock would be the best candidate to add to the existing portfolio and why.
