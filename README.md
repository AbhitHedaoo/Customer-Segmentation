# **Customer Segmentation using K-Means Clustering**

**Overview** - This repository contains a Python script that demonstrates the implementation of K-Means clustering for customer segmentation. Customer segmentation is a common application of clustering algorithms where customers are grouped into segments based on their similarities or patterns in purchasing behavior.

**Dataset** - The dataset used in this script is obtained from the file Mall_Customers.csv. It contains information about customers' annual income and spending score.

**Implementation** :

**Loading Dataset:** The dataset is loaded from the CSV file using the Pandas library. Only the features "Annual Income" and "Spending Score" are used for clustering.

**Finding Optimal Number of Clusters:** The Elbow Method is used to find the optimal number of clusters. This method helps in determining the appropriate number of clusters by plotting the within-cluster sum of squares (WCSS) for different numbers of clusters.

**Fitting K-Means Model:** K-Means clustering is performed using the KMeans class from scikit-learn. The optimal number of clusters obtained from the Elbow Method is used. The fit_predict method is used to fit the model to the dataset and predict the cluster labels for each data point.

**Visualizing Clusters:** The clusters are visualized using a scatter plot. Each cluster is represented by a different color, and the centroids of the clusters are indicated by yellow markers. The X-axis represents the annual income of customers, while the Y-axis represents their spending score.
