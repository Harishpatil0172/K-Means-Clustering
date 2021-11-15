# K-Means-Clustering-Customer-Segmentation
Goal:Understand about customers coming up in mall. Performed steps of data profiling, data preprocessing and exploratory data analysis on the dataset. Used K-Means clustering  for clusters formation and Visualizing all the Clusters

It is an iterative algorithm that divides the unlabeled dataset into k different clusters in such a way that each dataset belongs only one group that has similar properties.
K-Means Clustering is an Unsupervised Learning algorithm, which groups the unlabeled dataset into different clusters. Here K defines the number of pre-defined clusters that need to be created in the process, as if K=2, there will be two clusters, and for K=3, there will be three clusters, and so on

![k-means-clustering-algorithm-in-machine-learning](https://user-images.githubusercontent.com/77626222/141734952-06c94ced-701c-4ac2-9857-797ed9c3e598.png)

# How does the K-Means Algorithm Work?

The working of the K-Means algorithm is explained in the below steps:

    Step-1: Select the number K to decide the number of clusters.

    Step-2: Select random K points or centroids. (It can be other from the input dataset).

    Step-3: Assign each data point to their closest centroid, which will form the predefined K clusters.

    Step-4: Calculate the variance and place a new centroid of each cluster.

    Step-5: Repeat the third steps, which means reassign each datapoint to the new closest centroid of each cluster.

    Step-6: If any reassignment occurs, then go to step-4 else go to FINISH.

    Step-7: The model is ready.
