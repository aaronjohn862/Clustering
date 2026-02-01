# Iris Dataset Clustering using Unsupervised Learning

## Objective
The objective of this project is to apply clustering techniques to the Iris
dataset and analyze how data points are grouped without using class labels.

## Dataset
The Iris dataset is loaded from the sklearn library. It contains 150 samples
with four numerical features:
- Sepal length
- Sepal width
- Petal length
- Petal width

The species column was not used since clustering is an unsupervised learning task.

## Preprocessing
- Loaded the Iris dataset from sklearn
- Dropped the species column
- Applied feature scaling using StandardScaler to normalize the data

## Clustering Algorithms Implemented

### 1. KMeans Clustering
KMeans clustering groups data points into K clusters by minimizing the distance
between points and cluster centroids. It is suitable for the Iris dataset
because the data has well-separated clusters and numerical features.

### 2. Hierarchical Clustering
Hierarchical clustering builds clusters in a bottom-up manner by merging the
closest clusters. It is suitable for small datasets like Iris and provides
better interpretability using dendrograms.

## Visualization
- Scatter plots were used to visualize clusters
- A dendrogram was used to visualize hierarchical clustering

## Conclusion
Both KMeans and Hierarchical clustering performed well on the Iris dataset.
KMeans provided fast clustering, while hierarchical clustering offered better
interpretability.


