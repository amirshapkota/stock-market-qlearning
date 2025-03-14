# stock-market-qlearning

StockMarket class represent the stock market by changing the price of a stock at each step.

Trader class represent an agent that interacts with the stock market using Q-learning and decid whether to buy, sell, or hold based on the market's price.

Working:

The stock price fluctuates at each step.

The trader observes the recent price history (up to 10 steps), decides whether to buy, sell, or hold based on their Q-learning algorithm, and updates their balance accordingly.

The Q-table is updated after every action, allowing the trader for the best long-term rewards (maximizing their balance).

The final balance of the trader is plotted over the 1000 simulation steps
