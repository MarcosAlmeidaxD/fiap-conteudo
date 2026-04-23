# Cap 13 - Estimação e Discriminação RevFinal.pdf

**File type:** PDF | **Processed:** 2026-04-23

## TL;DR
A guide to separating data classes using Linear (LDA) and Quadratic (QDA) Discriminant Analysis in Python, focusing on the geometric differences between classifiers.

## What's Inside
- **Classifier Comparison:** Visual breakdown of why Decision Trees create "steps" while LDA/QDA produce clean lines and parabolic curves.
- **Python Workflow:** Step-by-step code for the `mtcars` dataset using `mpg` and `wt` to predict cylinder counts (`cyl`).
- **Data Prep:** Snippets for Log-Linear transformations to fix skewed distributions before running discriminants.
- **Performance Benchmarks:** A pros-and-cons table comparing accuracy across KNN, LDA, and QDA.

## Worth Knowing
Decision Trees use simple "if/then" logic that results in blocky, rectangular data splits. If your data classes aren't easily boxed in, LDA (for linear splits) or QDA (for curved, parabolic splits) usually provide a much tighter fit.
