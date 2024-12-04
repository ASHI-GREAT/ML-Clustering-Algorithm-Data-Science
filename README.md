# ML-Clustering-Algorithm-Data-Science
# Objective
This project explores the application of clustering techniques on the Iris dataset using KMeans Clustering and Hierarchical Clustering. It covers data preprocessing, implementation of clustering algorithms, and visualization of results.
# Data Loading and Preprocessing
Loading the Dataset: The Iris dataset is loaded using sklearn.datasets.load_iris().
Exclusion of Target Variable: The species column is excluded to focus on unsupervised clustering.
Feature Standardization: Features are standardized using StandardScaler to improve clustering accuracy and performance.
# Clustering Algorithm Implementation
1. KMeans Clustering
KMeans clustering partitions data into k clusters by minimizing variance within clusters. It iteratively updates cluster centroids until convergence. This method is well-suited for the Iris dataset due to its clear cluster separations.
2. Hierarchical Clustering
Hierarchical clustering builds a tree-like structure (dendrogram) of clusters to analyze hierarchical relationships in the data. Two approaches include:

Agglomerative Clustering: Start with individual points and iteratively merge clusters.
Divisive Clustering: Start with all points in one cluster and iteratively divide them.

# Conclusion
The project successfully implemented both KMeans and Hierarchical Clustering on the Iris dataset. The results align with the known structure of the dataset, demonstrating the effectiveness of these techniques in revealing inherent patterns.
