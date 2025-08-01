# K-Means Clustering Implementations  
**Author:** Anukul Pokharel  
**CRN:** 021-310  

---

## Overview

This project implements the **k-Means Clustering** algorithm in Python for clustering datasets with arbitrary features and cluster counts. It includes two versions:

- **k-Means for 2 features with k=2 clusters**  
- **Generalized k-Means for arbitrary features and clusters (tested with 4 features, k=3)**

Both versions use Euclidean distance and random centroid initialization, iterating until convergence or a max of 100 iterations.

---

## Features

- From-scratch k-Means implementation using NumPy  
- Random centroid initialization  
- Stopping criteria: centroid convergence or 100 iterations  
- Outputs cluster assignments and centroid positions  
- Computes Within-Cluster Sum of Squares (WCSS) for quality evaluation  
- Visualizes clusters with scatter plots  
  - 2D plot for 2-feature data  
  - Projection on first two features for datasets with more than 2 features  

---

## Implementations

### 1. k-Means Clustering for 2 Features (k=2)

- Dataset: 10 samples with two features  
- Clusters data into 2 clusters  
- Visualizes results with cluster-colored scatter plot and centroids

![2 features k means](Assets/2fkmeans.png)

### 2. Generalized k-Means Clustering for Arbitrary Features

- Dataset: 12 samples with 4 features  
- Clusters data into 3 clusters (`k=3`)  
- Visualizes clusters by projecting onto the first two features

![generalized](Assets/genkmeans.png)

---

## Outputs

- Cluster assignments per data point  
- Final centroid coordinates  
- Within-Cluster Sum of Squares (WCSS)  
- Cluster visualization plot  

---
