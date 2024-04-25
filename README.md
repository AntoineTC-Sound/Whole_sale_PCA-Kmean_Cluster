### Overview

This project focuses on segmenting wholesale customers using unsupervised learning techniques, specifically KMeans clustering and Principal Component Analysis (PCA). The dataset used in this analysis comprises various product spending amounts of different customers, which serve as a foundation for understanding customer purchasing behaviors in a wholesale distribution channel.

### Objective

The primary goal of this project is to identify distinct segments within the wholesale customers based on their spending patterns across various product categories. This segmentation can help in tailoring marketing strategies, improving customer service, and optimizing product placement.

### Dataset

The dataset includes the annual spending in monetary units on diverse product categories such as Fresh, Milk, Grocery, Frozen, Detergents_Paper, and Delicatessen. Each row represents a different customer.

### Methodology

## Data Preprocessing

- Data Cleaning: Checked for missing values and outliers, ensuring the quality of the dataset for analysis.
- Feature Scaling: Applied normalization to scale the data, crucial for the effectiveness of KMeans and PCA.

## Principal Component Analysis (PCA)

- Dimensionality Reduction: Implemented PCA to reduce the dataset's dimensionality while preserving the variance, making the dataset easier to explore and visualize.
- Interpretation: Analyzed the principal components to understand the underlying structure of the data.

## KMeans Clustering

- Finding the Optimal Number of Clusters: Used the Elbow Method to determine the optimal number of clusters by calculating the within-cluster sum of squares (WCSS).
- Clustering: Applied the KMeans algorithm with the identified number of clusters to segment the customers.
- Analysis: Evaluated the characteristics of each cluster to identify distinct customer segments.

### Results

This section provides an overview of the key findings, such as the number of identified customer segments and their characteristics based on their spending patterns. (Note: This section should be updated with actual results from your analysis.)
