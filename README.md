# clustering-hands-on

Clustering analysis using K-Means and DBSCAN on the Iris dataset.

## Files

```
clustering-hands-on/
├── clustering_kmeans_dbscan.ipynb
├── README.md
└── plots/
    ├── 01_feature_distributions.png
    ├── 02_pair_plot.png
    ├── 03_elbow_silhouette.png
    ├── 04_kmeans_k2_to_k5.png
    ├── 05_kmeans_k3_analysis.png
    ├── 06_dbscan_kdist.png
    ├── 07_dbscan_grid.png
    └── 08_kmeans_vs_dbscan.png
```

## Results

| Algorithm | Config | ARI |
|---|---|---|
| K-Means | K=3 | 0.6201 |
| DBSCAN | eps=0.65, min_samples=5 | 0.5734 |

## Setup

```bash
pip install scikit-learn pandas numpy matplotlib seaborn scipy
jupyter notebook clustering_kmeans_dbscan.ipynb
```

## References

- Müller & Guido — *Introduction to Machine Learning with Python*, Ch. 3
- Géron — *Hands-On Machine Learning*, Ch. 8
