# Cap 04 - Análise Multivariada de Dados RevFinal.pdf

**File type:** PDF | **Processed:** 2026-06-01

## TL;DR
This guide breaks down Principal Component Analysis (PCA) for turning messy, correlated data columns into clean, manageable indices using Python.

## What's Inside
*   **The Workflow:** A 3-step process covering correlation assessment, defining component counts, and result interpretation.
*   **Math Foundations:** Simplified explanations of Eigenvalues (*autovalores*) and Eigenvectors (*autovetores*).
*   **Python Snippets:** Ready-to-copy code for `StandardScaler`, `screeplot` generation, and `FactorAnalysis`.
*   **Selection Criteria:** Specific rules for keeping components, including the "Eigenvalue > 1" rule and Explained Variance thresholds.
*   **Practical Example:** A step-by-step walkthrough using municipal data to create a quality-of-life index.

## Worth Knowing
PCA is specifically for reducing column dimensions; if you need to group similar rows or individuals, you should switch to Cluster Analysis instead. Also, if your variables aren't highly correlated from the start, this technique won't actually provide much benefit.
