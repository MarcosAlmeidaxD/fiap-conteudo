# Cap 11 - Análise descritiva com Python RevFinal.pdf

**File type:** PDF | **Processed:** 2026-04-22

## TL;DR
A practical guide to calculating descriptive statistics—mean, median, mode, and dispersion—using Python's Pandas and NumPy libraries.

## What's Inside
- **Central Tendency:** Implementation of `df.mean()`, `df.median()`, and `df.mode()` for finding "typical" values.
- **Handling Gaps:** Using `skipna=True` to calculate averages even when your dataset has missing (None/NaN) values.
- **Dispersion Metrics:** Code for Total Amplitude, Standard Deviation (`df.std()`), and Variance to measure data "spread."
- **Quick Snapshots:** Using `df.describe()` to generate a full statistical summary of a dataset (like the included Titanic example) in one command.
- **Outlier Detection:** Identifying anomalies and data skewness by comparing the mean against the median.

## Worth Knowing
The guide highlights that the mean is easily "poisoned" by outliers; if your mean is significantly higher than your median, you've likely got some extreme high-end values pulling the average up. Always check both to see if your data is symmetrical or skewed.
