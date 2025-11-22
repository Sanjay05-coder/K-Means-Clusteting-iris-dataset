# K-Means-Clusteting-iris-dataset
Project Overview

This project demonstrates the implementation of K-Means clustering on the Iris dataset without applying PCA. The goal was to group the dataset into clusters based on similarity in features such as petal length and petal width.

Steps Performed


Data Selection

Used the Iris dataset, which contains measurements of iris flowers (petal length, petal width, etc.).



Finding Optimal K (Number of Clusters)

Implemented a loop from k = 1 to 11.
Calculated Within-Cluster Sum of Squares (WCSS) for each k.
Plotted an Elbow Graph to identify the point where WCSS starts to flatten.
The elbow point indicated k = 3 as the optimal number of clusters.



Clustering

Applied K-Means with k = 3.
Assigned data points to clusters based on the nearest centroid using Euclidean distance.



Visualization

Plotted clusters and centroids on a 2D graph using petal length and petal width.
Each cluster was represented with a different color, and centroids were marked distinctly.




Key Insights

The Iris dataset naturally forms three clusters, which align with the three species of iris flowers.
K-Means uses distance-based grouping, making it effective for datasets with clear separation.


Why K-Means?

Simple and efficient for partitioning data into clusters.
Works well when clusters are spherical and evenly sized.


Output

Elbow Graph showing optimal k = 3.
Cluster Plot with three distinct clusters and their centroids.


Applications

Customer segmentation.
Pattern recognition.
Grouping similar items in large datasets.
