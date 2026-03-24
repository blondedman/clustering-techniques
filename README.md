# Clustering Techniques

data set used : [https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset)

## Comparing Clustering Models on the basis of several factors, such as: 
- evaluation parameters used
- data preprocessing tools used
- number of clusters to be formed (3, 5 or 7)

### Models Used:
- Spectral Clustering
- Agglomerative Clustering
- Gaussian Mixture Clustering

### Evaluation Parameters Used:
- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Index

### Data Preprocessing Tools Used:
- No Data Preprocessing
- Standardization + PCA
- Min-Max Scaling + Outlier Removal (using Interquartile Range)
- Log Transformation + Normalization
- Feature Selection (Variance Threshold) + Discretization
- Robust Scaling + Feature Engineering (using Polynomial Features)

## Final Results:
![results](https://github.com/blondedman/clustering-models-comparisons/blob/main/results.png?raw=true)

## Key Findings:
(best silhoutte scores and number of clusters for each data processing tool)

![findings](https://github.com/blondedman/clustering-models-comparisons/blob/main/findings.png?raw=true)
