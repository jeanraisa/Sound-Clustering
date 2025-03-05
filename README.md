# Sound-Clustering

This project focuses on clustering unlabeled sound data. The goal is  to extract meaningful features from sound data, reduce the dimensionality of these features, to improve cluster visualization, analyze clustering performance, and compare different approaches for real-world applications.

# Key Components

1. **Feature Extraction**:

* Use of Mel Spectrograms for Feature Extraction.
* Convert the extracted features into a NumPy array .

2. **Dimensionality Reduction**:

* **PCA**: Used to reduce high-dimensional data while preserving variance.
* **t-SNE**: Provides better cluster separability by preserving local relationships.

3. **Clustering Algorithms**:

* **K-Means**: Effective for well-structured, compact clusters but sensitive to outliers.
* **DBSCAN**: Handles noise and irregularly shaped clusters but depends on parameter tuning.

4. **Real-World Applications**:

* Medical imaging (DBSCAN for irregular tumor detection, K-Means for structured tissue classification)
* Customer segmentation (K-Means for structured groups, DBSCAN for outlier detection)

# Conclusion

This project highlights the importance of dimensionality reduction in improving clustering effectiveness and visualization. The choice of clustering method depends on data characteristics, making it crucial to test different approaches for optimal results

