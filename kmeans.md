## K-means Clustering on Hadoop MapReduce

*GitHub Repository Link:* <https://github.com/mikonguyen/K-means-on-MapReduce>

### Overview

The goal of this project was to implement K-means clustering algorithm from scratch on Hadoop MapReduce for big data analytics. The program was developed using Java. 

K-means algorithm is the most well-known and commonly used clustering method.

It takes the input parameter, k, and partitions a set of n objects into k clusters so that the resulting intra-cluster similarity is high whereas the inter-cluster similarity is low.

Cluster similarity is measured according to the mean value of the objects in the cluster, which can be regarded as the cluster’s ‘center of gravity’.

The algorithm proceeds as follows:
- Firstly, randomly selects k objects from the whole objects which represent initial cluster centers.
- Each remaining object is assigned to the cluster to which it is the most similar, based on the distance between the object and the cluster center.
- The new mean for each cluster is then calculated. This process iterates until the criterion function converges.

### Tools Utilised
- Java
- Hadoop MapReduce
