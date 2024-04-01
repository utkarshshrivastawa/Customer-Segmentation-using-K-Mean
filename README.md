# Customer-Segmentation-using-K-Mean-Clustering 

## Import Libraries: 
Essential libraries such as numpy, pandas, matplotlib.pyplot, seaborn, and KMeans from sklearn.cluster are imported for data manipulation, visualization, and clustering.

## Data Collection or Loading: 
The dataset, Mall_Customers.csv, is loaded into a pandas DataFrame. This dataset includes customer ID, gender, age, annual income, and spending score.

## Initial Data Exploration:

1. The first five rows of the dataset are displayed to understand its structure.
2. The shape of the DataFrame is checked to find out the number of rows and columns.
3. The dataset's information is printed to understand data types and non-null counts.
4. Null value checks are performed to ensure data quality.


## Data Preparation:

1. The relevant columns, specifically annual income and spending score, are extracted into a new variable x.
2. These features will be used for clustering.

## Determining the Number of Clusters with WCSS:

1. The Within-Cluster Sum of Square (WCSS) values for different numbers of clusters (1 to 10) are calculated to find the optimal number of clusters.
2. An elbow graph is plotted using WCSS values. The elbow point, where the decrease in WCSS value starts to diminish, indicates the optimal number of clusters.

## Applying K-Means Clustering:

1. K-Means clustering is applied to the dataset with the number of clusters set to 5, determined as optimal from the elbow graph.
2. The model predicts the cluster for each customer, resulting in a cluster label for each data point.
## Data Visualization:

1. The clusters are visualized on a scatter plot, with annual income on the x-axis and spending score on the y-axis. Each cluster is assigned a different color for distinction.
2. The centroids of the clusters, calculated by the K-Means algorithm, are also plotted to visualize the center of each cluster.

## Contributions:
Encourages contributions such as issue reporting or suggestions for improvements.
Offers a detailed guide for setting up the environment, running the code, and contributing to the project.
