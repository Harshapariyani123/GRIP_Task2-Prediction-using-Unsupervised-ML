# GRIP_Task2-Prediction-using-Unsupervised-ML

**Task** : From Iris dataset predict the optimum number of clusters and represent it visually.

![iris](https://github.com/Harshapariyani123/GRIP_Task2-Prediction-using-Unsupervised-ML/assets/45930784/5cb15df5-bf25-4954-bccf-f637bbd487dc)


Predicting the number of clusters for the Iris dataset using the K-means algorithm typically involves the following steps:

1. **Load the Dataset**: First, load the Iris dataset, which consists of samples of iris flowers with their respective features (sepal length, sepal width, petal length, petal width).
2. **Preprocess the Data**: preprocess the data using libraries numpy, pandas, Sklearn. Check null or missing values from dataset.
3. **Choose the Number of Clusters (k)**: The K-means algorithm requires you to specify the number of clusters beforehand.
_Elbow Method_: Plot the within-cluster sum of squares (WCSS) against the number of clusters. The optimal number of clusters is where the curve bends like an elbow.
**Elbow Method:** -The elbow method is a heuristic used in determining the optimal number of clusters 𝑘 in a dataset for clustering analysis, such as with K-means clustering. It is based on the idea that as the number of clusters increases, the within-cluster sum of squares (WCSS) will decrease. The optimal number of clusters is often located at the "elbow" point in a plot of the WCSS against the number of clusters.
4. **Apply K-means**: Initialize the K-means algorithm with the chosen number of clusters and fit it to the data.
5. **Evaluate the Clustering** : evaluate the quality of the clustering. Visualizing the clusters Interpreting the centroids to understand the characteristics of each cluster.






