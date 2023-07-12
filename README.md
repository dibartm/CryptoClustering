# CryptoClustering
Install the required dependencies:
scikit-learn
pandas
matplotlib
hvplot
Import the necessary modules in your Python environment.
Load the CSV file into a pandas DataFrame.
Normalize the data using the StandardScaler() module from scikit-learn.
Find the optimal value for k (the number of clusters) using the elbow method.
Perform clustering using K-means with the chosen k value.
Visualize the clusters using scatter plots.
Perform Principal Component Analysis (PCA) on the original scaled data.
Find the optimal value for k using the PCA data and perform clustering.
Conclusion:
This project demonstrates the process of clustering cryptocurrencies based on their price change patterns. It covers data normalization, the elbow method for determining the optimal number of clusters, and the use of Principal Component Analysis (PCA) for dimensionality reduction. By comparing clustering results on the original data and the reduced PCA data, you can observe the impact of using fewer features on the clustering outcome.
