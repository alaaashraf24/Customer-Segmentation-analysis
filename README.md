# Customer Segmentation Analysis

This Jupyter Notebook performs a comprehensive customer segmentation analysis using various clustering algorithms.  The goal is to identify distinct customer groups based on their financial behavior, enabling targeted marketing strategies and improved customer relationship management.

## Overview

The notebook employs the following techniques:

* **Data Preprocessing:** Handles missing values, outlier analysis (without removal in this case due to high outlier prevalence), and data transformation (log transformation for skewed features) to prepare the data for clustering.
* **Feature Engineering:**  The notebook uses existing features for analysis.  Potentially further feature engineering can be used to improve accuracy.
* **Dimensionality Reduction:** Principal Component Analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE) reduce the dimensionality of the data for visualization and efficient clustering.
* **Clustering Algorithms:**
    * K-means
    * Hierarchical Clustering
    * DBSCAN
    * Gaussian Mixture Model (GMM)
* **Model Evaluation:** The analysis uses the Elbow method, silhouette score, and Adjusted Rand Index (ARI) to evaluate the performance of each clustering algorithm.
* **Visualization:** Employs various plots (histograms, boxplots, scatter plots, dendrograms, radar charts) to explore data distributions, cluster structures, and customer profiles.

## Data

The analysis uses the "CC GENERAL.csv" dataset, which contains information about customer credit card usage.

## Requirements

The notebook relies on several Python libraries.  Ensure these are installed before running the notebook:

