Customer Segmentation using K-Means Clustering - Task 02
​
​Project Overview
​-This project applies the K-Means Clustering algorithm to group customers of a retail store based on their purchase history, specifically focusing on their Annual Income and Spending Score.

​Dataset
​-The project uses the Mall Customers Dataset from Kaggle.

​Implementation Details
​The code performs the following steps:
​-Data Loading: Reads the Mall_Customers.csv file using Pandas.
​-Feature Selection: Selects 'Annual Income' and 'Spending Score' for clustering.
​-Elbow Method: Uses the Within-Cluster Sum of Square (WCSS) to find the optimal number of clusters (K).
​-Clustering: Applies the KMeans algorithm to segment the data.
​-Visualization: Plots the Elbow Method graph and the final customer clusters.

​Libraries Used
​-Pandas: For data handling.
​-Matplotlib: For creating the Elbow graph and cluster plots.
​-Scikit-learn: For the K-Means clustering algorithm.

​Files in this Repository
​-task2.py: The Python script containing the clustering logic.
​-Mall_Customers.csv: The dataset used for analysis.
​-Figure_1.png: The Elbow Method graph.
​-customer_segmentation.png: The final visualization of grouped customers
