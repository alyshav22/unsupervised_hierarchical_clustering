# unsupervised_hierarchical_clustering

Hierarchical clustering provides an alternative approach to k-means clustering for distinguishing groups in the dataset.
This approach can be subdivided into two types: agglomerative hierarchical clustering (AHC) and diverse hierarchical clustering. 
With AHC each observation is initially regarded as a cluster of its own. In contrast, diverse hierarchical clustering provides an inverse of AHC. 
It starts with the root, where all objects are included in one cluster. Afterward, the most heterogeneous clusters are iteratively divided until
all observations are in their own cluster. The output of hierarchical clustering is a tree-based representation of the observations, called a dendrogram. 
The observations could be subdivided into groups by cutting the dendrogram at the desired similarity level. In this project, we will use the USArrests 
dataset to perform hierarchical clustering. The dataset contains the number of arrests for murder, assault, and rape for each of the 50 states in 1973.
