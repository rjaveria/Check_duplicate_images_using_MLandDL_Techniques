# Check_duplicate_images_using_MLandDL_Techniques

### Project Objective:
The objective of the project is to identify and remove duplicate images in the dataset using machine learning and deep learning algorithms. To achieve this, clustering algorithms are employed to group similar images into respective clusters, allowing for the efficient removal of duplicates. This process results in a clean and organized dataset, facilitating better future decision-making.

### Libraries and Algorithms:
Numpy, Keras, Matplotlib, cv2, Dbscan, Kmeans

### Kmean Clustering Algorithm:
- Use Elbow Method to identify the optimal numbers of clusters in the dataset.
- Running clustering algorithm with optimal k value and create a cluster directory  to store images in their respective clusters.
- To analyze the performance of clustering algorithm,the silhouette analysis method is used to check how well the images clustered in their respective cluster.

### Dbscan Clustering Algorithm:
- Compute the dbscan algorithm to identify the estimated number of clusters,noise points,homogeneity score, v_measure and silhouette coefficient to check the dataset and store it in their respective cluster location after removing noise.
- Plot the results using matplotlib to check the formation of clusters and the noise values that is ignored.

### Final Result:Duplicated images removed per clustered:
There are total 804 duplicate images is detected in the given dataset that is removed to clean the data for future analysis.
1) Cluster 1: 25% of images identify as duplicated images.
2) Cluster 2: 59%  of images identify as duplicated images.
3) Cluster 3: 14% of images identify as duplicated images.
