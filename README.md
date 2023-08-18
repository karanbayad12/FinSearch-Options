# Option Pricing Models
Black-Scholes Merton, Monte Carlo sim 

parameters needed to import:  
ticker, strike price, expiry date, risk-free rate, volatility  

Option pricing models are implemented in [Python 3.7](https://www.python.org/downloads/release/python-377/). Latest spot price, for specified ticker, is fetched from Yahoo Finance API using [pandas-datareader](https://pandas-datareader.readthedocs.io/en/latest/). Visualization of the models through simple web app is implemented using [streamlit](https://www.streamlit.io/) library.  

data is fetched from Yahoo Finance API using pandas-datareader, it's cached with [request-cache](https://github.com/reclosedev/requests-cache) library is sqlite db, so any subsequent testing and changes in model parameters with same underlying instrument won't result in duplicated request for fethcing already fetched data.





 



