****Customer Segmentation using K-Means and Hierarchical Clustering****

his repository contains a comprehensive analysis and implementation of customer segmentation using K-means and Hierarchical clustering techniques on a large-scale dataset with over 1 million rows. The primary objective of this project is to segment customers based on their transaction behaviors, enabling targeted marketing strategies and enhanced customer satisfaction.


****Table of Contents****

**Introduction**

- Dataset
- Project Structure
- Installation
- Data Preprocessing
- Clustering Techniques
- K-Means Clustering
- Hierarchical Clustering
- Results and Visualizations

**Introduction**

Customer segmentation is a crucial aspect of modern business strategy, allowing companies to understand their customer base and tailor their products, services, and marketing efforts accordingly. In this project, we apply both K-means and Hierarchical clustering algorithms to categorize customers based on their transaction patterns, derived from a large dataset of banking transactions.

**Dataset**

The dataset used in this project consists of over 10 million transaction records, including the following columns:

- TransactionID
- CustomerID
- CustomerDOB
- CustGender
- CustLocation
- CustAccountBalance
- TransactionDate
- TransactionTime
- TransactionAmount (INR)

**Data Preprocessing**

Given the size and complexity of the dataset, significant preprocessing steps were undertaken, including:

- Handling Missing Values: Imputation or removal of missing data.
- Outlier Detection and Removal: Identifying and excluding outliers to ensure accurate clustering.
- Feature Scaling: Standardizing features using StandardScaler for uniformity across variables.
- Data Transformation: Conversion of categorical variables to numerical values using techniques like one-hot encoding.

****Clustering Techniques****

**K-Means Clustering**

- Optimal Cluster Determination: Utilized the Elbow Method to identify the optimal number of clusters.
 Implementation: Applied K-means clustering to segment customers into distinct groups.
- Visualization: Generated 2D and 3D scatter plots to visualize the clusters and analyze their characteristics.


**Hierarchical Clustering**

- Dendrogram Construction: Built a dendrogram to visualize the hierarchical clustering process.
- Agglomerative Clustering: Applied agglomerative clustering to create hierarchical customer segments.
- Cluster Visualization: Produced visual representations of the hierarchical clusters and compared them with K-means results.


****Results and Visualizations****

- K-means Results: The K-means algorithm identified distinct customer segments, which were visualized using scatter plots.

- Hierarchical Clustering: Hierarchical clustering provided a complementary view of customer segments, illustrated through dendrograms and cluster plots.


















