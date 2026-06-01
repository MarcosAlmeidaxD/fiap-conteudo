# Cap 06 - Redes neurais multicamadas RevFinal.pdf

**File type:** PDF | **Processed:** 2026-06-01

## TL;DR
This guide explains how to move beyond simple linear models to Multilayer Perceptrons (MLP) to solve complex, non-linear problems like XOR and image recognition.

## What's Inside
- **The XOR Problem**: Visual proof of why single-layer Perceptrons fail at non-linear classification (Figures 1-3).
- **Architecture Blueprints**: Specific criteria for choosing the number of hidden layers, neuron counts, and topology.
- **Weight Initialization**: Detailed breakdowns of **He** and **Xavier** strategies to ensure the network actually learns.
- **Backpropagation & Gradients**: A deep dive into the math of error correction and the "vanishing gradient" bottleneck.
- **Python Hands-on**: 12 code snippets covering everything from data splitting to building multi-layer models for the Iris and MNIST datasets.

## Worth Knowing
Weight initialization (He vs. Xavier) is the "make or break" step here; pick the wrong one and your gradients will likely explode or vanish before the first epoch finishes. The note also emphasizes that while more layers add power, they drastically increase the risk of overfitting (addressed in Section 5).
