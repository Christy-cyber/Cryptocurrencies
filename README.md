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

## Results and Summary
Principal Components Analysis (PCA) was used to reduce preprocessed data to three dimensions after data were scaled.  An elbow curve was created to find the best value for "K" that resulted in four n_clusters that were used to initialize the K-Means model. A 3-D scatter plot showed four distinct groupings of cryptocurrencies based on three Principal Components (Fig. 1). A 2-D scatter plot highlighted four groupings when "Total Coin Supply" was plotted against "Total Coins Mined" (Fig. 2).  There were 532 tradable cryptocurrencies.

![3D_PCA_plot](https://user-images.githubusercontent.com/95387273/164569687-10ec9960-9745-4f85-9af8-f8fd1cf71275.png)

Fig. 1. 3-D scatter plot showing four clusters.
_________________________________________________________________________________________________________________________________________________________________________

![2D_Plot](https://user-images.githubusercontent.com/95387273/164569702-e8056c62-3398-4555-810f-9b45c74aca7f.png)

Fig 2. 2-D scatter plot highlighting four clusters.
