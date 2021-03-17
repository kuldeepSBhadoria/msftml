# msftml
Problem:

Pick a number of centroids to start for a 2D dataset
Assign data points to a centroid randomly to initialize
Plot points and assignments
Compute new cluster centroids
Reassign data points to a new centroid based on euclidian distances and plot
Repeat 4 and 5

Kuldeep 3/16 11:47 PM Solution:

We will assume we will have 10 clucters for 1,11 in for loop
We will use KMeans function for initilaize the cluster of random state
Once wcss ready we will plot the Elbow to get the best cluster count
As we get the cluster we will apply KMeans using fit_predict(X)
Then we will plot all the clusters and centroids
