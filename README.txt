### This project is inspired by the recent surge in retail investors and the popularity of "Reddit Stocks" which are stocks of certain companies that are widely disucssed on the social media site, Reddit. These new retail investors are mostly youths who have received extra disposable cash from stimulus checks during the Covid-19 pandemic, and have no better place to park their cash, especially with the near-zero interest rate environment. We want to explore the relationship between  the volume/price of these "Reddit stocks" versus the frequency of mentions on social media (Reddit).


### This project is separated into 3 portions:
1. Scraping of Reddit for frequency of mentions of certain stock tickers.
2. Using of AlphaVantage API to do data exploration and visualisation. 
3. Using LSTM and ARIMA models to predict stock price of certain tickers. 

Please go through the notebooks in the following order: scrapeReddit, linearRegression, lstm, ARIMA

Description of each notebook:

scrapeReddit: We used this to scrape Reddit to get the data that we wanted
linearRegression: In this notebook, we used our data from Reddit as well as data from Alpha Vantage Stock API to perform linear regrssion
lstm: Used an lstm model to try to predict stock price
ARIMA: Used an ARIMA model to predict stock price

Detailed explanations are in the notebooks, as well as in the video presentation. A copy of the presentation slides has been included here

Thank you! 
