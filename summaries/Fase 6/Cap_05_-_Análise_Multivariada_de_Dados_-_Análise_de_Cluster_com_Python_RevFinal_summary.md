# Cap 05 - Análise Multivariada de Dados - Análise de Cluster com Python RevFinal.pdf

**File type:** PDF | **Processed:** 2026-06-01

## TL;DR
A practical manual for performing unsupervised machine learning (Cluster Analysis) in Python, bridging the gap between statistical theory and RFM business applications.

## What's Inside
* **Theory & Distinctions:** Deep dive into why similarity (Euclidean distance) is used for grouping instead of correlation.
* **Pre-processing Workflow:** Specific instructions for variable selection, outlier handling, and data normalization using Min-Max and Standard scaling.
* **Algorithm Toolbox:** Comparison of Hierarchical methods (Dendrograms and Agglomeration Coefficients) versus Non-Hierarchical methods (K-Means).
* **Validation Metrics:** How to use the Elbow Method (WCSS) and Silhouette scores to determine the "correct" number of clusters.
* **Python Implementation:** Code snippets using `scikit-learn`, `scipy`, and `pandas` for segmenting customers based on Recency, Frequency, and Monetary (RFM) data.

## Worth Knowing
The workflow suggests a hybrid approach: use Hierarchical clustering and Dendrograms first to find the ideal number of groups, then apply K-Means to actually assign the individuals. This balances visual intuition with computational efficiency.
