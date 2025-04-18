# Clustering Evaluation on UCI Wine Dataset (Google Colab)

This Colab notebook performs a comprehensive clustering analysis on the UCI Wine dataset using different clustering algorithms, preprocessing strategies, and evaluation metrics.

## Dataset
- **Source**: UCI Machine Learning Repository
- **Dataset**: Wine Dataset
- **Features**: 13 continuous attributes of wine samples
- **Target**: 3 classes of wine

## Clustering Algorithms Implemented
- KMeans Clustering
- Agglomerative (Hierarchical) Clustering
- Mean Shift Clustering

## Preprocessing Methods
- No Preprocessing
- Normalization (StandardScaler)
- Power Transformation (PowerTransformer)
- PCA (Principal Component Analysis)
- Combined: Transform + Normalization
- Combined: Transform + Normalization + PCA

## Evaluation Metrics
- Silhouette Score
- Calinski-Harabasz Score
- Davies-Bouldin Score

## Cluster Configurations Tested
- Number of clusters: 1, 2, 3

## Output
- Tables with evaluation metrics for each clustering algorithm and preprocessing combination.
- CSV files saved to the Colab environment:
  - `kmeans_wine_clustering_results.csv`
  - `hierarchical_wine_clustering_results.csv`
  - `meanshift_wine_clustering_results.csv`
  - `combined_wine_clustering_results.csv`

## Summary
- The notebook identifies and prints the best clustering configuration based on the Silhouette Score.
- Helpful for comparing preprocessing pipelines and clustering performance in unsupervised learning.

## How to Use
1. Open the notebook in Google Colab.
2. Run all cells sequentially.
3. Review printed tables and download result CSVs if needed.

## Author
Built with ❤️ using Python, Scikit-learn, and Google Colab.