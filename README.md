# Principal-Component-Analysis
### Python 3 + Jupyter Notebook + Latex

## Principal Component Analysis - Review 

Principal Component Analysis (PCA) is an unsupervised linear transformation technique that is widely used across different fields, most prominently for feature extraction and dimensionality reduction. Other popular applications of PCA include exploratory data analyses and de-noising of signals in stock market trading, and the analysis of genome data and gene expression levels in the field of bioinformatics.

PCA helps us to identify patterns in data based on the correlation between features. In a nutshell, PCA aims to find the directions of maximum variance in high-dimensional data and projects it onto a new subspace with equal or fewer dimensions than the original one.

### Content
1. Introduction
2. Load data
3. Standardization of the data
4. Construct the covariance matrix
5. Decompose the covariance matrix into its eigenvectors and eigenvalues.
6. Sort the eigenvalues by decreasing order to rank the corresponding eigenvectors.
7. Explained variance - select k eigenvectors which correspond to the k largest eigenvalues, where k is the dimensionality of the new feature subspace (k ≤ d).
8. Projection Matrix - Construct a projection matrix W from the “top” k eigenvectors
9. Transform the d-dimensional input dataset X using the projection matrix W to obtain the new k-dimensional feature subspace
10. PCA implementation
11. PCA application example
12. Conclusion
13. References
