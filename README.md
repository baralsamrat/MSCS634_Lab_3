# MSCS634_Lab_3
# K-Means and K-Medoids Clustering on Wine Dataset

## Purpose
This lab explores **unsupervised learning** through clustering on the Wine Dataset using **K-Means** and **K-Medoids** algorithms.  
It aims to evaluate how well each method partitions the data into groups that correspond to the natural wine classes.

## Methodology
- Standardized all 13 chemical features using z-score normalization.  
- Applied **K-Means** and **K-Medoids** with k = 3.  
- Calculated **Silhouette Score** and **Adjusted Rand Index (ARI)** to evaluate cluster quality.  
- Visualized the clusters using PCA for 2D projection.

## Key Findings
- **K-Means** achieved higher Silhouette Scores, indicating better-defined clusters.  
- **K-Medoids** was more robust to potential outliers and easier to interpret (medoids = real data points).  
- Both methods revealed structure aligned with the true labels.

## Insights
- **K-Means** is efficient and ideal for large, spherical data distributions.  
- **K-Medoids** is preferred for smaller datasets or when interpretability and robustness are important.

## Challenges
- Choosing the correct number of clusters and handling K-Medoids’ computational cost.  
- Visualizing 13D data effectively in 2D required PCA dimensionality reduction.

## Conclusion
Both clustering techniques performed well, but **K-Means** yielded higher cohesion, while **K-Medoids** provided robustness and clarity in interpretation.
