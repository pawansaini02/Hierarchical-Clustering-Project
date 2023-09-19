# Hierarchical Clustering Project


Here in this project we are performing hierarchical clustering, where the input is a set of points, with a score that represents the pairwise similarity or dissimilarity of the points. The goal is to output a tree, often binary, whose leaves represent data points, and internal nodes represent clusters.


Hierarchical clustering creates the hierarchical decomposition of database. The algorithm iteratively split the database into smaller subset, until some termination condition is satisfied. The hierarchical clustering algorithms do not need k as an input parameter, which is an advantage over partitioning algorithms. The hierarchical decomposition can be represented by dendrogram in two ways.
I. Bottom-up (agglomerative) approach
II. Top-down (Divisive) approach.
The basic agglomerative, hierarchical clustering algorithm works as following ways Initially each object is placed in a unique cluster. For each pair of clusters, some value of dissimilarity or distance is computed. For instance, the distance may be in minimum distances (Single linkage) in the current clustering are merged, until the whole data sets forms a single cluster.
