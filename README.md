# Iris-Clustering
## Objective
This project demonstrates the application of clustering algorithms on the classic Iris dataset. The goal is to uncover natural groupings in the data using:

- **KMeans Clustering**
- **Hierarchical Clustering**

and visualize the results with **PCA** for dimensionality reduction.

---

## Dataset
The Iris dataset from the `sklearn` library contains 150 samples with 4 features:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

The dataset originally contains species labels, which were excluded since clustering is an unsupervised technique.

---

## Methodology

### 1. Data Preprocessing
- Loaded the Iris dataset.
- Standardized features using `StandardScaler` to normalize the data.
- Applied PCA to reduce data to 2 principal components for visualization.

### 2. Clustering Algorithms
- **KMeans Clustering**: Partitioned data into 3 clusters by minimizing within-cluster variance.
- **Hierarchical Clustering**: Created a cluster hierarchy via agglomerative linkage, visualized with a dendrogram.

### 3. Visualization
- Used PCA to project data into 2D space.
- Visualized cluster assignments with scatter plots colored by cluster label.
- Created a dendrogram to understand cluster relationships in Hierarchical Clustering.

---

## Results

- Both KMeans and Hierarchical clustering successfully identified 3 distinct clusters corresponding closely to the known Iris species.
- PCA plots clearly showed separation between clusters.
- The dendrogram provided insights into the nested structure of clusters in the dataset.
