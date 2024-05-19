# Crypto Clustering Challenge
---
**Brief Description**: This challenge uses a combination of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes:
> - *Part 1: Cluster Cryptocurrencies using K-means* - Find the best value of `k` and cluster cryptocurrencies using K-means based on the preparation of the original scaled dataset.
> - *Part 2: Optimize clusters using Principal Component Analysis (PCA)* - Find the best value of `k` and cluster cryptocurrencies using K-means based on the PCA dataset.<br>

**Inputs**: The challenge takes in as input a sample dataset that contains the different crypto currency clusters. The corresponding input file is named as *crypto_market_data.csv*. <br>

**Outputs**: The challenge provides the following outputs as described below:
> - *Line Charts*: A Line chart with all the inertia values computed with the different values of `k` to visually identify the optimal value for `k` for each of original and PCA data.    
> - *Scatter Plots*: A scatter plot using *hvPlot* that colors all the graph points with the labels found using K-means for each of original and PCA data. 
> - *Composite Plots*: By using *hvPlot* and the plus sign operator (`+`), two separate composite plots that each compare the elbow curve and cryptocurrency clusters from the original data to that of PCA data.<br>

**References**:
> - hvPlot Documentation: Composing Plots, https://holoviz.org/tutorial/Composing_Plots.html, accessed May 2024.
> - Principal Component Analysis (PCA), https://www.geeksforgeeks.org/principal-component-analysis-pca, accessed May 2024.
> - Elbow Method and K-means Clustering, https://www.analyticsvidhya.com/blog/2021/01/in-depth-intuition-of-k-means-clustering-algorithm-in-machine-learning, accessed May 2024. 
---
