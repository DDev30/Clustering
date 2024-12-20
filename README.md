
---

# Clustering Analysis on Wine Dataset

This project demonstrates clustering analysis performed on the Wine dataset from the UCI Machine Learning Repository. Various clustering techniques, including K-Means, Hierarchical Clustering, and Mean-Shift, were evaluated using key clustering metrics. The notebook also includes preprocessing steps such as normalization and an evaluation of different cluster sizes.

## Dataset
The dataset used is the **Wine dataset**, which contains 13 features representing the chemical analysis of wines grown in the same region in Italy.

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/wine/)

### Features
- Alcohol
- Malic Acid
- Ash
- Magnesium
- Flavanoids, etc.

## Clustering Techniques
The following clustering techniques were analyzed:
1. **K-Means Clustering**
2. **Hierarchical Clustering**
3. **Mean-Shift Clustering**

## Evaluation Metrics
To evaluate the performance of clustering, the following metrics were used:
- **Silhouette Score**: Measures how similar each point is to its own cluster versus other clusters.
- **Calinski-Harabasz Index**: Evaluates the ratio of the sum of the between-cluster dispersion and the within-cluster dispersion.
- **Davies-Bouldin Index**: Measures average similarity between clusters, with lower values indicating better clustering.

## Results
The results were presented in a tabular format for each clustering technique, showing metrics for different preprocessing steps and the number of clusters (`c=3`, `c=4`, `c=5`). Below is a snippet of the table format:

```
Performance using K-Means Clustering
+-------------+----------------+---------------------+------------------+
| Clusters    | Silhouette     | Calinski-Harabasz  | Davies-Bouldin   |
+-------------+----------------+---------------------+------------------+
| c=3         |                |                    |                  |
| c=4         |                |                    |                  |
| c=5         |                |                    |                  |
+-------------+----------------+---------------------+------------------+
```

## Tools and Libraries
- **Python**
- **Pandas**
- **Scikit-learn**
- **Matplotlib** (optional, for further visualization)

## Conclusion
- **K-Means Clustering** performed well for smaller clusters based on Silhouette Score.
- **Hierarchical Clustering** showed better separation for larger cluster sizes.
- **Mean-Shift Clustering** provided consistent results but was slower on larger datasets.

## Repository Structure
- **`clustering_analysis.ipynb`**: Contains the clustering implementation.
- **`README.md`**: Documentation file (this file).
- **`sample_results_table.png`**: Example of result presentation.

## References
- UCI Wine Dataset: [Link](https://archive.ics.uci.edu/ml/machine-learning-databases/wine/)
- Scikit-learn Documentation: [Link](https://scikit-learn.org/)

---

