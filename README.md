# Cryptocurrencies

## Purpose
The purpose of this project is to filter through dirty/unsupervised data, process and clean it up, and to create clusters of information that we are able to use later on. We will be reducing the clusters into dimensions and filter through a PCA to analyze the crypto-market.
Our goal for this project is to create a report that helps to identify what cryptocurrencies are being traded in the market. We will be using  PCA, K-means, hvplots and clustering algorithms to help visualize the data.

## Analysis / Results
![PC data](https://github.com/benlew3/Cryptocurrencies/blob/main/images/PCA.PNG)<br>
In the image above, we are looking at the data for our PCA algorithm that is helping to reduce the dimensions. This is generated from sifting through our original data to generate the new data frame index. <br>

![Elbow curve](https://github.com/benlew3/Cryptocurrencies/blob/main/images/elbow.PNG) <br>
In the image above, we are looking at the elbow curve, where we are able to see the break at point for, then shifts to a strong horizontal line to point 10. The elbow makes this is a k=4. <br>
![Cluster Data](https://github.com/benlew3/Cryptocurrencies/blob/main/images/cluster.PNG) <br>
From building the K-Mean model into the 4 clusters, we then generate a new clean crypto dataframe that shows the various PCs as well as how the coins are moving. This new dataframe is created to showcase the data clusters. <br>

![3D graph](https://github.com/benlew3/Cryptocurrencies/blob/main/images/3d%20cluster.PNG) <br>
In the image above, we are showing a 3-D scatter plot that represents the PCA data in clusters. This shows three classes of principal components by the different classes.<br>

![scatterplot](https://github.com/benlew3/Cryptocurrencies/blob/main/images/hvplot%20scatter.PNG) <br>


## Difficulties
