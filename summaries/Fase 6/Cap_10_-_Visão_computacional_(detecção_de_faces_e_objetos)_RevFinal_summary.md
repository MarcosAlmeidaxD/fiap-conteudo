# Cap 10 - Visão computacional (detecção de faces e objetos) RevFinal.pdf

**File type:** PDF | **Processed:** 2026-04-24

## TL;DR
A technical deep dive into Computer Vision, tracking the evolution from classic contour detection to modern deep learning models like YOLO and SSD.

## What's Inside
*   **Core Concepts:** Defines the gap between simple classification (labels), localization (bounding boxes), and segmentation (pixel masks).
*   **Classic Methods:** Implementation guides for Haar Cascades (faces) and SIFT (objects) using traditional image processing.
*   **Modern Architectures:** Practical use of pre-trained networks including **VGG16**, **MobileNet**, and **AlexNet**.
*   **The TensorFlow Pipeline:** Step-by-step code for data augmentation, CSV structuring, model compilation, and saving weights.
*   **Hands-on Lab:** A "challenge" section focused on building a custom detector using a specific dataset.

## Worth Knowing
Object detection is essentially a two-part job: a classifier identifies the "what," while a localization function draws the "where" using bounding boxes. The provided code snippets show exactly how to bridge that gap by adapting pre-trained classification models into functional detectors.
