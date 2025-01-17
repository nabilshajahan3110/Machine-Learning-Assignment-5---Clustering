## Machine-Learning-Assignment-5---Clustering
An assignment in Jupyter Notebook covering Clustering.

### Objective:
The assignment aims to evaluate understanding and application of clustering techniques (KMeans and Hierarchical Clustering) on the Iris dataset.

### Tasks Performed:

**1. Loading and Preprocessing**

**Dataset:** The Iris dataset was loaded from sklearn.

**Data Preprocessing:** Converted the dataset into a DataFrame. Dropped the species column to align with the clustering problem (unsupervised learning).

**Standard Scaling:** Applied StandardScaler to standardize the features, ensuring all variables contribute equally to the clustering process.

### 2. KMeans Clustering

**Description:** KMeans partitions data into k clusters by minimizing intra-cluster variance.

**Implementation:**

Applied KMeans clustering with 3 clusters (based on domain knowledge of the Iris dataset).

Visualized clusters using scatter plots for the first two principal components.

**Insights:**

The model reasonably separated the data into clusters resembling the natural grouping of the Iris species.

**Silhouette score for KMeans: 0.494.**

### 3. Hierarchical Clustering

**Description:** Builds a hierarchy of clusters by either merging (agglomerative) or splitting (divisive) clusters.

**Implementation:**

Used agglomerative clustering with 3 clusters.

Visualized the dendrogram and final clusters using scatter plots.

**Insights:**

The dendrogram showed the hierarchical structure of data points.

**Silhouette score for Hierarchical Clustering: 0.450.**

### 4. Silhouette Analysis

**Metric:** Silhouette score was calculated for both clustering methods to evaluate the quality of clustering.

**Result:**

KMeans clustering performed slightly better with a higher silhouette score.

### 5. Insights Gained:

**KMeans vs. Hierarchical Clustering:**

KMeans clustering had a higher silhouette score, indicating better-defined clusters. Both methods reasonably separated the data, but KMeans performed slightly better due to its focus on minimizing intra-cluster variance.

**Effect of Standard Scaling:**

Standard scaling was crucial in clustering, as it ensured that all features contributed equally regardless of their scales.

**Silhouette Scores:**

Both clustering techniques produced moderately high silhouette scores, suggesting well-separated clusters for the Iris dataset.

### Conclusion:

The assignment demonstrates a solid understanding of clustering methods.

KMeans clustering is slightly more suitable for the Iris dataset based on silhouette scores.

Visualizations and evaluation metrics (like the silhouette score) were effectively used to assess clustering quality.
