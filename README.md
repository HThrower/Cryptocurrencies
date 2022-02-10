# Crypto_Clustering

This analysis looks at the different types of cryptocurrencies and how they should be grouped towards creating a classification. This was done by undertaking these 4 tasks:

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
