# Anomaly Detection Comparison

This notebook demonstrates and compares various anomaly detection algorithms on different synthetic datasets. 
We'll explore the performance of algorithms like One-Class SVM, Isolation Forest, and Local Outlier Factor.

The decision boundaries and computation times vary significantly across algorithms and datasets, highlighting the importance of selecting the appropriate method based on the data characteristics.

# Outlier Detection on Wine Dataset

In this notebook, we'll explore different outlier detection algorithms using the `wine` dataset from `sklearn`. 
We will compare `Empirical Covariance`, `Robust Covariance (Minimum Covariance Determinant)`, and `One-Class SVM` by visualizing their decision boundaries.

We use two-variable subsets from the Wine dataset to illustrate different outlier detection methods. While this visualization is in 2D, high-dimensional cases are more complex.
