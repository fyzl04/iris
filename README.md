# Formative Assessment: Unsupervised Learning on Iris Dataset

## Objective
This project evaluates the application of clustering techniques on the Iris dataset, focusing on KMeans and Hierarchical clustering.

---

## Dataset
The dataset used is the **Iris dataset** from the `sklearn` library. It contains information about three species of Iris flowers and features like sepal length, sepal width, petal length, and petal width.

---

## Project Tasks and Components

### 1. **Loading and Preprocessing** 
- The Iris dataset was loaded using `sklearn.datasets`.
- As this is a clustering problem, the **species column** was dropped from the dataset.

### 2. **Clustering Algorithm Implementation** (8 marks)

#### A) **KMeans Clustering** 
- **Description:** KMeans clustering is a partitioning method that groups data points into `k` clusters based on their features. It minimizes the variance within clusters.
- **Why suitable for Iris dataset?**: The Iris dataset is well-suited for KMeans as it contains distinct clusters corresponding to flower species, making it ideal for separating data points based on similarity.
- **Steps:**
  - Applied KMeans with `n_clusters=3`.
  - Visualized the clusters using a scatter plot.

#### B) **Hierarchical Clustering** 
- **Description:** Hierarchical clustering builds a tree-like structure (dendrogram) by either agglomerating or dividing data points based on their similarity.
- **Why suitable for Iris dataset?**: This method captures nested relationships and provides insights into the dataset's natural groupings.
- **Steps:**
  - Performed Agglomerative Clustering with `n_clusters=3`.
  - Generated a dendrogram for better visualization.
  - Visualized the clusters using a scatter plot.


---

## Visualizations
- Scatter plots for KMeans and Hierarchical clustering clearly illustrate the formed clusters.
- A dendrogram provides additional insight into the hierarchical structure of the dataset.

---

## Files
- **`iris.ipynb`**: Contains all the code, visualizations, and explanations for the project.

---

## How to Run
1. Clone this repository:
   ```bash
   git clone <repository-link>
