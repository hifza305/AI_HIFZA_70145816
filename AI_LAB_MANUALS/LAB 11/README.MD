LAB No 11
Agglomerative Hierarchical Clustering

Question 1: 
Perform Agglomerative Clustering with Different Linkages. 
Task:
Load the "shopping-data.csv" dataset, extract the features Annual Income and Spending Score, and perform Agglomerative Clustering using:
•	linkage = "ward"
•	linkage = "complete"
•	linkage = "average"
Instructions:
1.	Perform clustering using AgglomerativeClustering.
2.	Plot the clusters using matplotlib.
3.	Compare how the cluster structure changes with each linkage method.

Question 2:
Draw a Dendrogram and Identify the Optimal Number of Clusters
Task:
Using the same dataset or any synthetic dataset, draw a dendrogram using:
from scipy.cluster.hierarchy import dendrogram, linkage

Instructions:
1.	Fit the data using linkage(method='ward').
2.	Plot a dendrogram.
3.	From the dendrogram, visually determine:
o	The optimal number of clusters
o	The height at which clusters merge
4.	Explain why hierarchical clustering may be preferred over K-Means.

Question 3: Compare Agglomerative vs Divisive Hierarchical Clustering
Task:
Using a small synthetic dataset (e.g., 10–12 points), perform:
•	Agglomerative Clustering
•	Divisive Clustering (manual split or using a library like sklearn-extra)
Instructions:
1.	Plot dendrograms for both methods.
2.	Compare the merge/split patterns.
3.	Describe:
o	Why agglomerative is more common in practice
o	Which method is more computationally expensive
o	Which gives clearer cluster boundaries for small datasets
