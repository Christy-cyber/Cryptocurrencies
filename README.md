# Cryptocurrencies
## Overview and Purpose
The purpose was to use unsupervised machine learning to determine what cryptocurrencies were on the trading market and how they could be grouped in order to create a classification system for a new cryptocurrency investment portfolio.  This process included:
  - Preprocessing data for PCA
  - Reducing data dimensions using PCA
  - Clustering Cryptocurrencies using K-means
  - Visualizing results in 2-D and 3-D graphs

## Resources
- Data Source: crypto_data.csv (data obtained from https://min-api.cryptocompare.com/data/all/coinlist)
- Software and Programming Languages: Jupyter Notebook v. 6.4.6; Python v. 3.8.3 :: Anaconda, Inc.; conda v. 4.11.0; scikit-learn v. 0.23.1:: Anaconda, Inc.

## Results
Principal Components Analysis (PCA) was used to reduce preprocessed data to three dimensions after data were scaled.  An elbow curve was created to find the best value for "K" that resulted in four n_clusters that were used to initialize the K-Means model. A 3-D scatter plot showed four distinct groupings of cryptocurrencies based on three Principal Components. A 2-D scatter plot highlighted four groupings when "Total Coin Supply" was plotted against "Total Coins Mined."

## Summary
There were 532 tradable cryptocurrencies.
