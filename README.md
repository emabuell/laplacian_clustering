# laplacian_clustering
Short Jupyter notebook for clustering using spectral coordinates

In this small project I implemented Laplacian (or spectral) coordinate embedding to cluster point clouds whose topological structure is not Gaussian-mixture like.
The main idea is to construct a graph structure from the point cloud using a kernel to control connection. Spectral coordinates are new coordinates constructed ad hoc to minimize the average euclidean distance between graph-connected points in the new space, in order to reobtain a Gaussian-mixture like point cloud.
Some small tests are performed on artificial data.
