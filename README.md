# CryptoClustering
This project clusters cryptocurrencies based on market data using K-means clustering. It involves plotting the elbow curve, optimizing clusters with PCA, and comparing prediction results of the original data and the PCA data.

## Files

- **Resources**: This folder contains the csv file provided, `crypto_market_data.csv`.
- **Crypto_Clustering.ipynb**: This Jupyter notebook contains the Python code and unsupervised learning process for predicting cryptocurrency changes.

## Overview of the stages

* Data Preparation: Normalize the data using `StandardScaler()` and set up the DataFrame.
* Elbow method: Find the optimal number of clusters using elbow method and plot the curve.
* Clustering: Cluster the cryptocurrencies using `Kmeans`.
* Optimize Clusters with PCA: Apply PCA to reduce dimensionality and improve clustering.
* Evaluate Results: Compare the performance of the clustering models.
