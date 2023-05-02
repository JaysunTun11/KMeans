README: Python Implementation of K-Means Clustering

This implementation is a Python implementation of the K-Means clustering algorithm, which is a popular unsupervised learning technique used for clustering and 
segmentation of data. The goal of K-Means is to partition a dataset into K clusters, where each cluster contains instances that are similar to each other based on 
some distance metric.

The K-Means algorithm works as follows:

1. Initialize K cluster centroids randomly from the data points in the dataset.
2. Assign each instance to the nearest centroid based on some distance metric, typically Euclidean distance.
3. Recalculate the centroids of each cluster as the mean of all instances assigned to that cluster.
4. Repeat steps 2 and 3 until convergence is reached, i.e., the centroids no longer move significantly between iterations.
5. The output of the K-Means algorithm is a set of K cluster centroids and a partitioning of the instances into K clusters.

The K-Means algorithm is useful for many applications, including image segmentation, customer segmentation, and anomaly detection. However, the 
quality of the clusters obtained depends heavily on the choice of K and the initialization of the centroids. Various techniques exist for choosing K, such as the 
elbow method and the silhouette method, while initialization techniques include random initialization and k-means++ initialization.

This implementation includes the ability to choose K, specify the distance metric used for clustering, and use k-means++ initialization. Additionally, this 
implementation includes the option to visualize the clustering results using scatter plots and heatmaps.
