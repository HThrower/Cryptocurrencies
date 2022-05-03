# Crypto_Clustering

The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.

## Goals and steps

* Data Preprocesing to prepare for dimension reduction with PCA and clustering using K-Means
* Reducing Data Dimensions Using PCA
* Clustering Cryptocurrencies Using K-Means
* Visualizing Results to create plots

## Data Visulization

*a 3D scatter plot using Plotly Express to plot the clusters using the clustered_df DataFrame.
This plot includes the following parameters on the plot: hover_name="CoinName" and hover_data=["Algorithm"] to show this additional info on each data point:

![image](https://user-images.githubusercontent.com/31675832/153492928-eb9bfdc1-7f4e-42c0-81ef-9c1810e4e7c5.png)

*a scatter plot using hvplot.scatter to present the clustered data about cryptocurrencies.
This plot has x="TotalCoinsMined" and y="TotalCoinSupply" to contrast the number of available coins versus the total number of mined coins. Use the hover_cols=["CoinName"] parameter to include the cryptocurrency name on each data point:

![image](https://user-images.githubusercontent.com/31675832/153493062-30047938-e5cd-4ee2-8837-aea29fefc79e.png)

## Summary 

We have identified the classification of 532 cryptocurrencies based on similarities of their features.
Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.


