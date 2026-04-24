# Cap 11 - Visão computacional (reconhecimento de faces e objetos) RevFinal.pdf

**File type:** PDF | **Processed:** 2026-04-24

## TL;DR
A technical guide for implementing high-speed face detection and recognition using YuNet, VGG-Face, and the OpenCV Model Zoo.

## What's Inside
*   **YuNet Implementation:** Details on using this ultra-lightweight detector (75k parameters) for millisecond-level face tracking on CPUs.
*   **VGG-Face Workflows:** Step-by-step logic for extracting feature vectors (embeddings) and calculating cosine similarity to distinguish between individuals.
*   **Multi-Task Learning:** Architecture and code for simultaneous age, gender, and emotion prediction using the UTKFace dataset.
*   **Real-Time Pipelines:** Specific Python snippets (Codes 9, 18, and 23) for moving from static image analysis to live video stream processing.
*   **Performance Metrics:** Instructions for generating learning curves and confusion matrices to validate model accuracy.

## Worth Knowing
YuNet is positioned as a superior alternative to Haar Cascades and YOLOv4 for edge devices because it handles challenging lighting and angles while maintaining a tiny memory footprint. Remember: detection must always precede recognition in these pipelines to define the ROI.
