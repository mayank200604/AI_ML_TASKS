Task 8 🌸 Customer Segmentation with K-Means Clustering

This project demonstrates unsupervised learning using K-Means clustering on the Mall Customers dataset. The goal is to group customers into meaningful clusters based on their Annual Income and Spending Score, and to evaluate clustering performance using the Elbow Method and Silhouette Score.

📌 Project Overview

The Mall Customers dataset contains customer demographic and spending information, which can be used for customer segmentation in marketing strategies.

This project involves:

1.Loading and preparing the dataset

-Selecting relevant features: Annual Income (k$) and Spending Score (1-100)
-Feature scaling using StandardScaler

2.Applying K-Means clustering

-Assigning customers to different clusters
-Extracting cluster centroids

3.Finding the optimal number of clusters

-Using the Elbow Method (inertia vs k)

4.Visualizing clusters in 2D

-Scatter plot of Income vs Spending Score with cluster color-coding
-Centroids plotted as black "X" markers

5.Evaluating cluster quality

-Using the Silhouette Score to measure separation between clusters


⚙️ Requirements

Install the following Python libraries:

pip install numpy pandas matplotlib scikit-learn
