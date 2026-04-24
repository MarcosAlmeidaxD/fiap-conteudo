# Cap 03 - Técnicas de ensemble learning RevFinal.pdf

**File type:** PDF | **Processed:** 2026-04-24

## TL;DR
Deep dive into Ensemble Learning, focusing on how combining "weak" models like Random Forest and XGBoost beats using a single "pure" algorithm.

## What's Inside
* **Bagging vs. Boosting:** Clear breakdown of parallel processing (Random Forest) vs. sequential error correction.
* **The Modern Triplets:** Comparative benchmarks and launch timelines for **XGBoost** (2014), **LightGBM** (2016), and **CatBoost** (2017).
* **Bootstrap Logic:** Technical explanation of how generating multiple data samples reduces variance and prevents overfitting.
* **Python Lab:** Practical code (Page 15+) showing environment setup and `train_test_split` loops to compare booster performance.
* **Loss Functions:** Visualization of how different algorithms handle error minimization (Page 14).

## Worth Knowing
LightGBM is the efficiency king in this guide; it typically matches XGBoost’s accuracy but runs in only about 30% of the processing time. If you're dealing with categorical data, CatBoost (2017) is the one to flag for its specific optimizations.
