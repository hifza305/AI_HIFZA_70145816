LAB Assignment No 10
K means Clustering Schemes in Machine Learning

Question 1 
Write Python code to implement K-Means clustering from scratch using the following data points:
P1(1,3), P2(2,2), P3(5,8), P4(8,5), P5(3,9),
P6(10,7), P7(3,3), P8(9,4), P9(3,7)

Tasks:
1.	Use K = 3 clusters
2.	Initialize centroids as
•	C1 = P7(3,3)
•	C2 = P9(3,7)
•	C3 = P8(9,4)
3.	Perform 2 iterations manually in code
4.	Plot all points and centroids
5.	Label all points (P1…P9)
6.	Sketch the clusters using matplot library in python

Question No. 2
Use the scikit-learn KMeans() library to cluster the same points.
P1(1,3), P2(2,2), P3(5,8), P4(8,5), P5(3,9), P6(10,7), P7(3,3), P8(9,4), P9(3,7)
Tasks:
1.	Use K = 2, 3, and 4
2.	Plot the clustering result for each K
3.	Compare:
•	Number of points in each cluster
•	Final centroid locations
4.	Draw the 3 graphs in your lab copy and explain how the shapes change with K.

Question 3 — Add a New User Point and Re-Cluster
Given the original 9 points, add a new user: P10(6,2)
Tasks:
1.	Run K-Means using K = 3
2.	Plot the graph with all 10 points
3.	Identify:
•	Which cluster P10 joins
•	How centroids shift after adding P10
4.	Sketch before/after clusters in notebook
5.	Write a short explanation about how a new data point affects clustering.

Question 4 — Distance Table + First Iteration Manually
Using the given 9 points and initial centroids:
C1(3,3), C2(3,7), C3(9,4)

Tasks:
1.	Compute Euclidean distance of each point to each centroid (manually or in python)
2.	Create a distance table:
