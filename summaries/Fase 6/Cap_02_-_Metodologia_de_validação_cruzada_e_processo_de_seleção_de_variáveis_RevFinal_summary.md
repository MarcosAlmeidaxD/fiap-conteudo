# Cap 02 - Metodologia de validação cruzada e processo de seleção de variáveis RevFinal.pdf

**File type:** PDF | **Processed:** 2026-06-01

## TL;DR
A technical deep dive into balancing model accuracy with simplicity using cross-validation and penalized regressions (Ridge/Lasso) in Python.

## What's Inside
*   **Bias vs. Variance Trade-off:** Conceptual framework for minimizing error while ensuring the model generalizes to new data.
*   **Penalty Functions:** Mathematical breakdown of **L1 (Lasso)** and **L2 (Ridge)** regularization to control model complexity.
*   **Python Implementation:** Step-by-step source code for data prep, cross-validation indices, and model tuning.
*   **PSA Case Study:** Real-world application showing how to handle correlations and select relevant variables from a raw dataset.

## Worth Knowing
The guide argues that complex models are often business liabilities; it prioritizes "simplicity" (regularization) not just for performance, but to make results explainable to non-technical stakeholders. If your model is too hard to explain to a client, it's probably overfitted.
