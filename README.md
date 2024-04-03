# Project

## In this project, the objective was to explore the use of market sentiment extracted from financial news for creating a trading strategy.  

### After collecting and refining relevant data, including stock prices and financial headlines, we used different ML models  of getting the sentiments for the news and for each approach we calculated the correlation between sentiment scores and event-related stock returns. Notably,  the lexicon-based VADER approach showed the highest correlation and was chosen for sentiment scoring in the trading strategy. The trading strategy generates buy, sell, and hold signals based on the sentiment change and the relationship between the stock price and the 15-day moving average. For example a buy signal is generated if the sentiment change (i.e: current sentiment score - previous sentiment score) is greater than a threshold parameter and the stock price is above the 15-day moving average
