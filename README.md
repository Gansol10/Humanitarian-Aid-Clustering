# Humanitarian-Aid-Clustering
Overview

This project focuses on identifying countries that require humanitarian aid based on various socio-economic and environmental factors. By utilizing clustering techniques, the project categorizes countries into distinct groups to prioritize aid distribution effectively.

Objective

- Clustering countries based on factors influencing humanitarian aid needs.

- Providing insights into prioritizing aid efforts for maximum impact.

Dataset

Source: Humanitarian Aid Dataset (https://www.kaggle.com/datasets/hellbuoy/pca-kmeans-hierarchical-clustering)

 - Size: Approx. 200MB

 - Format: CSV

 - Features:

   - GDP per capita

   - Population density

   - Access to clean water

   - Literacy rate

   - Unemployment rate

   - Natural disaster frequency

Technology Stack

- Programming Languages: Python

- Libraries: Pandas, Numpy, Seaborn, Matplotlib, Scikit-learn, Scipy

- Techniques: Principal Component Analysis (PCA), K-Means Clustering, Elbow Method, Silhouette Analysis

Workflow

1. Data Preprocessing:

 - Handling missing values and outliers.

 - Normalizing numerical features for clustering.

2. Feature Reduction:

 - Apply PCA to reduce dimensionality while retaining important variance.

3. Clustering:

 - Using the K-Means algorithm to group countries based on their features.

 - Determining the optimal number of clusters using the Elbow Method and Silhouette Analysis.

4. Visualization:

 - Visualizing cluster distributions in 2D space.

 - Highlighting key characteristics of each cluster.

Results and Insights

Cluster Profiles:

Cluster 1: Countries with relatively stable socio-economic indicators and lower need for immediate aid.

Cluster 2: Countries with high socio-economic challenges and a greater need for humanitarian assistance.

Key Factors:

Access to clean water and GDP per capita were the most influential features in cluster assignments.
