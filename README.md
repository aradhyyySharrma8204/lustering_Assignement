# Clustering_Assignement\
# 🧠 Clustering Algorithms Evaluation with Dimensionality Reduction

This project evaluates the performance of different clustering algorithms combined with dimensionality reduction techniques to identify the best-performing pair using metrics like **Silhouette Score** and **Calinski-Harabasz Index**.

---

## 📊 Algorithms Evaluated

- **K-Means**
- **Agglomerative Clustering**
- **DBSCAN**
- **Gaussian Mixture Models (GMM)**

---

## 🧮 Dimensionality Reduction Techniques

- **PCA (Principal Component Analysis)**
- **t-SNE (t-distributed Stochastic Neighbor Embedding)**

---

## 📈 Evaluation Metrics

- **Silhouette Score**: Measures how well clusters are defined; higher values indicate better-defined clusters.
- **Calinski-Harabasz Index**: The ratio of between-cluster dispersion to within-cluster dispersion; higher is better.

---

## 🥇 Best Result

- **Algorithm**: `DBSCAN`
- **Preprocessing**: `PCA`
- **Silhouette Score**: `0.798` ⭐️ *(Best among all tested combinations)*

---

## 📌 Observations

- DBSCAN with PCA produced the highest silhouette score, indicating it best captured the natural structure in the data.
- PCA generally improved clustering results over t-SNE.
- GMM showed consistent but not top-tier performance.
- K-Means and Agglomerative Clustering were competitive but slightly behind DBSCAN in most cases.

---

## 📁 Project Structure


