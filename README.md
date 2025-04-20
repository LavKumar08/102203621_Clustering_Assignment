# 102203621_Clustering_Assignment
# 📊 Clustering Evaluation on the Iris Dataset

This project applies and evaluates various clustering algorithms on the classic **Iris dataset** using different preprocessing techniques and metrics.

---

## 📁 Project Structure

- **Dataset**: `sklearn.datasets.load_iris()` – contains 150 samples with 4 numerical features.
- **Algorithms Used**:
  - **KMeans**
  - **Agglomerative Clustering**
  - **DBSCAN**
- **Preprocessing Methods**:
  - None (Raw Data)
  - Standard Scaling
  - Min-Max Scaling

---

## 🚀 Objective

To evaluate the effectiveness of clustering algorithms by applying:
- Different preprocessing methods
- Multiple cluster sizes (`n_clusters = 2, 3, 4`)
- Clustering evaluation metrics

---

## 📐 Evaluation Metrics

| Metric                  | Goal             | Description                                                                 |
|-------------------------|------------------|-----------------------------------------------------------------------------|
| **Silhouette Score**    | Higher is better | Measures similarity within a cluster vs other clusters (range: -1 to 1).   |
| **Calinski-Harabasz**   | Higher is better | Ratio of between-cluster to within-cluster dispersion.                     |
| **Davies-Bouldin Score**| Lower is better  | Measures average similarity between each cluster and its most similar one. |

---

## ✅ Best Performing Algorithm

| Preprocessing | Algorithm        | n_clusters | Silhouette Score |
|---------------|------------------|------------|------------------|
| `none`        | Agglomerative    | 2          | **0.6867**       |

- 📌 **Conclusion**: Agglomerative Clustering with 2 clusters and no preprocessing gives the best result based on the **Silhouette Score**.

---

## 📊 Visualizations

- **Silhouette Score Comparison Chart** across all combinations.
- **PCA Scatter Plots** for top 3 clustering configurations to visualize cluster separability.

---
