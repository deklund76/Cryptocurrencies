# Cryptocurrencies

This repository contains a jupyter notebook meant to act as a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for investing. The data was retrieved from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist). Using the Scikit Learn machine learning library, the data was first cleaned and encoded, before being decomposed into principal components. Intertias for different numbers of clusters were then calculated and plotted to determine the K value for K-means clustering. The data was then assigned to clusters and the final part of the notebook summarizes the findings through plots and tables using hvplot and plotly express.
