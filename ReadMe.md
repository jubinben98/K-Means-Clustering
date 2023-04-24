### About the project

<br>
<img src="https://miro.medium.com/v2/resize:fit:1080/1*fz-rjYPPRlGEMdTI-RLbDg.png">
<br> <br>

This is an implementation of K-means clustering algorithm in Python. K-means is a commonly used unsupervised machine learning algorithm that aims to group similar data points into a given number of clusters. The code defines a class KMeans with methods to fit, predict, and return cluster centroids.

The constructor takes the number of clusters as an argument, and initializes other variables such as the clusters dictionary, data length, threshold for convergence, and seed for random number generation. The fit method generates the clusters iteratively by calculating the Euclidean distance between each data point and the centroids of the clusters and assigning each data point to the nearest cluster. It then updates the centroids based on the mean of the data points in each cluster until convergence.

The predict method assigns new data points to the nearest cluster, and the cluster_centroids method returns the final centroid coordinates. The code also includes methods to calculate Euclidean distance and reset the element list for the next iteration.

Overall, this code provides a basic implementation of the K-means algorithm that can be used to cluster datasets with a given number of clusters. However, it may not be optimized for large datasets or datasets with high dimensionality.
