# K-Means Clustering with Elbow Method

## Overview

This project performs K-Means clustering on a dataset named `train.csv` to identify user behavior patterns based on various features. The process involves data preprocessing, normalization, and clustering, followed by visualization of the clustered data using the Elbow method to determine the optimal number of clusters.

## Key Steps

### 1. Data Loading and Preprocessing

- **Data Upload**: The dataset is uploaded and read into a Pandas DataFrame.
- **Data Cleaning**: Missing values are removed using `dropna()`.
- **Data Normalization**: Selected columns are normalized using `StandardScaler` to ensure all features contribute equally to the clustering process.

### 2. Elbow Method for Optimal Clusters

The Elbow method helps in determining the optimal number of clusters by plotting the inertia (sum of squared distances of samples to their nearest cluster center) against the number of clusters.

#### Process:

- **Optimization Function**: Define a function `optimise_k_means` to compute and plot inertia for different numbers of clusters.
- **Elbow Plot**: Generate an Elbow plot to visualize the optimal number of clusters.

### 3. K-Means Clustering

- **Model Fitting**: Apply K-Means clustering with the chosen number of clusters.
- **Label Assignment**: Assign cluster labels to the data points.
- **Visualization**: Plot the clustered data for different features to analyze the clustering results.

### 4. Visualizations

Multiple visualizations are created to understand the clustering results and to compare different numbers of clusters.

#### Visualizations Include:

- **Scatter Plots**: Display clusters for various feature combinations.
- **Multiple Cluster Comparisons**: Show clustering results for different numbers of clusters to help in selecting the best one.

## Conclusion

This project demonstrates the use of the Elbow method for determining the optimal number of clusters and visualizing the clustering results for a user behavior dataset. By following these steps, you can gain insights into user patterns and group similar users together.



