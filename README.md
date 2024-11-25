# Iris-Clustering-Algorithm-Unsupervised
### Overview
This unsupervised learning techniques, specifically KMeans and Hierarchical Clustering, on the Iris dataset. The goal is to explore how clustering algorithms can group data based on their features without the use of target labels, as it is a clustering problem in an unsupervised setting.

### Dataset
Source: The Iris dataset from scikit-learn.
Description: The dataset consists of 150 samples of Iris flowers, each with 4 features (sepal length, sepal width, petal length, and petal width) and 3 possible species.
### Objective
Clustering the dataset into 3 clusters (one for each species).
### Exploring unsupervised learning techniques: KMeans and Hierarchical Clustering.
Clustering Algorithms Implemented
### KMeans Clustering:

Divides data into k clusters by assigning each point to the nearest centroid and adjusting centroids until they stabilize.
### Why suitable for Iris dataset: The dataset has well-separated clusters, making it ideal for KMeans to form clear groupings based on features.
### Hierarchical Clustering:

Builds a tree-like structure (dendrogram) that shows how data points are grouped together based on similarity.
### Why suitable for Iris dataset: Hierarchical clustering helps visualize the relationships between clusters, even when the exact number of clusters is not known in advance.

### Steps Followed in the Project
- Loading and Preprocessing:
- Loaded the Iris dataset.
- Dropped the target column (species) as clustering is an unsupervised task.
### KMeans Clustering:
- Applied KMeans to the dataset.
- Visualized the clusters in 2D using PCA.
### Hierarchical Clustering:
- Applied Agglomerative (Hierarchical) Clustering.
- Visualized the clusters using a dendrogram and 2D scatter plot.
### Visualizations
- KMeans: A scatter plot showing 3 clusters in 2D space.
- Hierarchical: A dendrogram to visualize how the clusters are formed and a scatter plot of the clusters.

### Conclusion
Here it demonstrates the use of unsupervised learning techniques (KMeans and Hierarchical Clustering) to find patterns and groupings in the Iris dataset without the use of target labels. It showcases how clustering algorithms can reveal structure in data based purely on the features.
