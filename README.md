# Crypto Clustering
## Repository Structure:
In this repository, the main file will be "Crypto_Clustering.ipynb" with the .csv file sitting tight in the "Resources" folder.

## Quick Overview:
In this class assignment I've used my knowledge of Python and unsupervised learning (specifically K-means clustering as well as Principal Component Analysis (PCA) on clustering) to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Steps to reach final conclusion:
1. Find the Best Value for k Using the Original Scaled DataFrame
2. Cluster Cryptocurrencies with K-means Using the Original Scaled Data
3. Optimize Clusters with Principal Component Analysis
4. Find the Best Value for k Using the PCA Data
5. Cluster Cryptocurrencies with K-means Using the PCA Data
6. Visualize and Compare the Results

## Final Conclusion:
  * **Question:** After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

  * **Answer:** Based on my analysis of the clustering results, I observed that reducing the number of features has a noticeable impact on K-means clustering. In the first plot with fewer features, the elbow method suggested that 4 clusters was the optimal choice. However, upon further inspection, a division into 2 or 3 clusters might have yielded clearer separations.
  When I used PCA data with more features, the elbow curve still indicated a k-value of 4. Yet, the resulting cluster plot showed a more distinct separation among the clusters, which made it easier to visually interpret the data. Despite this, the ideal number of clusters, based on visual assessment, seemed to be 3, as it provided a more coherent grouping.
  Therefore, while the elbow curve consistently suggests 4 clusters, a practical evaluation of the cluster plots indicates that fewer clusters might result in a clearer partitioning of the data.
