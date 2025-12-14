# Unsupervised Learning: Clustering Analysis

This repository contains a comprehensive analysis of **Unsupervised Machine Learning** techniques applied to dataset segmentation. The goal of this project is to identify distinct groups (clusters) within the data to uncover hidden patterns and insights without labeled outcomes.

It was a project for an Artificial Intelligence course.

## Authors
* **[Luis Orofino]**
* * **[Daniel Casquero]**

## Project Overview

In this project, we explore various clustering algorithms to segment data based on similarities. The workflow includes:

1.  **Exploratory Data Analysis (EDA):**
    * Data distribution visualization.
    * Correlation analysis (Heatmaps).
2.  **Data Preprocessing:**
    * Feature Scaling (StandardScaler/MinMaxScaler).
    * Handling missing values (if applicable).
    * Dimensionality Reduction using **PCA** (Principal Component Analysis) for visualization.
3.  **Clustering Algorithms Applied:**
    * **K-Means Clustering:** Iterative centroid-based grouping.
    * **Hierarchical Clustering:** Agglomerative approach with Dendrograms.
    * **DBSCAN:** Density-based spatial clustering (optional, if you used it).
4.  **Model Evaluation:**
    * **Elbow Method:** To determine the optimal number of clusters (*k*).
    * **Silhouette Score:** To validate the consistency within clusters.


To run this notebook locally, install the necessary dependencies:

```bash
pip install -r requirements.txt
