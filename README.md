# Cryptocurrency Clusters

## Background
A prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. We will be helping determine whether cryptocurrencies currently trading can be grouped to create a classification system.

There is no known classification system for cryptocurrency, and so we will first need to process the raw data to fit machine learning models to use unsupervised learning. Several clustering algorithms will be used to explore whether cryptocurrencies can be grouped together with other similar cryptocurrencies.

<hr>

## Data Preparation
* Read `crypto_data.csv` into Pandas. The dataset was obtained from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist).
* Filtered for currencies that are currently being traded.