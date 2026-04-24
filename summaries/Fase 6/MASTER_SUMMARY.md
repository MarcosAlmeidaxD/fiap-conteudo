# File Processing Report

**Source folder:** `Fase 6`  
**Processed:** 2026-04-24  
**Files analysed:** 19

---

## 08 - STO - Financeiro_RevFinal.pdf `PDF`

## TL;DR
A crash course on designing a scalable startup financial model that grows revenue exponentially without bloating costs.

## What's Inside
* **Scalability Matrix:** Comparison between traditional "linear" business models (consultancies) vs. scalable platforms (Spotify/Airbnb).
* **Projection Framework:** A 12-period (1-year) roadmap to visualize cash flow behavior.
* **Input vs. Output Mapping:** Specific sections for revenue streams (sales, commissions) and expenses (initial investments vs. variable costs).
* **Tax & Activity Configs:** How to categorize the business by industry (Product, Service, or Industry) to fix tax calculations.
* **5-Year Estimations:** Guidelines for projecting long-term growth and expense trends based on first-year data.

## Worth Knowing
The guide pushes a "pessimistic first" strategy—if the math doesn't hold up in a worst-case scenario, the model is broken. Also, it specifically references a FIAP-provided Excel template where you should only touch the green cells to avoid breaking the logic.

---

## 09 - STO - Pitch_RevFinal.pdf `PDF`

## TL;DR
A crash course on hacking the human brain to deliver high-stakes pitches that actually get a "yes."

## What's Inside
- **Pitch Hierarchy:** Breakdown of the Tweet Pitch (140 chars), Elevator Pitch (60s), and the deep-dive Investment Pitch (20m).
- **The Limbic Hack:** Why you must pitch to the "primitive brain" (instinct) before the "neocortex" (logic) to avoid being ignored.
- **Oren Klaff’s Rules:** Four filters the brain uses to kill boring presentations—if it’s not new or unexpected, it's invisible.
- **Persuasion Framework:** Moving from *explaining* what a product does to *convincing* someone they need it.
- **The Momentum Strategy:** Using "windows of opportunity" (Economic/Social/Tech shifts) to create a sense of urgency.

## Worth Knowing
Investors filter out 90% of what they hear as "threats" or "noise." If your pitch doesn't trigger a novelty response in the limbic system immediately, the listener's brain literally stops processing your data.

---

## 2TSCOR Challenge MaterDei 2oSem 2025 v2 RevFinal.pdf `PDF`

[Gemini error: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}]

---

## Cap 01 - INTELIGÊNCIA ARTIFICIAL NA ERA DO E-COMMERCE RevFinal (1).pdf `PDF`

[Gemini error: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}]

---

## Cap 01 - INTELIGÊNCIA ARTIFICIAL NA ERA DO E-COMMERCE RevFinal.pdf `PDF`

## TL;DR
Final project brief to build a sales prediction model for "Melhores Compras" and translate the technical "why" for a non-tech board.

## Numbers & Dates
- **Dataset:** `sales.csv` (7 key variables including CPI and Unemployment).
- **Scale Adjustments:** Divide `Fuel_Price` and `Unemployment` by 1,000 to get real values.
- **Project Year:** 2025.

## What This Means
The coding part is the easy bit; even a basic linear regression might work. The real challenge is the "so what?" factor—you have to defend your choice and explain your model’s accuracy to a board that doesn't know what a p-value is. It's about showing how external factors like gas prices and holidays actually dictate the company's future.

## Next Move
- **Clean the data first:** Make sure to scale those two specific columns before training, or your model will be junk.
- **Translate the jargon:** Prepare a presentation that skips the math and focuses on business strategy—prepare them for economic expansion or contraction.

---

## Cap 02 - Metodologia de validação cruzada e processo de seleção de variáveis RevFinal.pdf `PDF`

[Gemini error: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}]

---

## Cap 03 - Técnicas de ensemble learning RevFinal.pdf `PDF`

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

---

## Cap 04 - Análise Multivariada de Dados RevFinal.pdf `PDF`

[Gemini error: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}]

---

## Cap 05 - Análise Multivariada de Dados - Análise de Cluster com Python RevFinal.pdf `PDF`

[Gemini error: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}]

---

## Cap 06 - Redes neurais multicamadas RevFinal.pdf `PDF`

[Gemini error: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}]

---

## Cap 07 - Práticas de Redes neurais multicamadas RevFinal.pdf `PDF`

[Gemini error: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}]

---

## Cap 08 - Pipeline de Deep Learning RevFinal (1).pdf `PDF`

## TL;DR
A technical deep-dive into Deep Learning pipelines, covering core architectures (CNN, RNN, GAN) and hands-on TensorFlow implementation for unstructured data.

## What's Inside
- **Architecture Specs**: Detailed breakdowns of CNNs for computer vision, RNNs/LSTMs for sequences, and GANs for generative tasks.
- **Hardware Benchmarks**: Visual comparisons of CPU vs. GPU performance for large-scale matrix operations.
- **Data Augmentation**: Specific strategies for expanding image and text datasets to prevent overfitting.
- **Code Implementation**: Python snippets using TensorFlow and Keras to build, train, and evaluate a model using the Fashion MNIST dataset.
- **Pipeline Workflow**: The end-to-end cycle from vector representation of raw data to model deployment.

## Worth Knowing
Deep Learning eliminates the need for manual feature engineering by learning hierarchical representations directly from raw data—crucial since 80% of modern data is unstructured. The guide also highlights that while traditional ML performance plateaus, DL scales almost linearly with more data and GPU power.

---

## Cap 08 - Pipeline de Deep Learning RevFinal.pdf `PDF`

[Gemini error: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}]

---

## Cap 09 - Redes neurais convolucionais (CNNs) RevFinal.pdf `PDF`

[Gemini error: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}]

---

## Cap 10 - Visão computacional (detecção de faces e objetos) RevFinal.pdf `PDF`

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

---

## Cap 11 - Visão computacional (reconhecimento de faces e objetos) RevFinal.pdf `PDF`

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

---

## Cap 13 - Redes neurais recorrentes RevFinal.pdf `PDF`

## TL;DR
A technical guide to mastering sequential data modeling using RNNs and LSTMs, complete with a Keras-based stock price prediction project.

## What's Inside
- **Architectural Breakdowns:** Visual comparisons between standard Feedforward RNAs and Recurrent (RNN) structures, including "unfolded" representations.
- **The Gradient Problem:** Detailed explanation of the Vanishing Gradient issue and why it limits simple RNNs to short-term memory.
- **LSTM & GRU Gating:** Deep dive into the "Forget," "Input," and "Output" gates that allow LSTMs to maintain long-term dependencies.
- **Stock Market Lab:** Python code snippets (Keras/TensorFlow) for scaling data, creating time-series datasets, and calculating RMSE for price predictions.
- **Use Case Directory:** Quick list of applications ranging from speech recognition (Google/Siri) to medical signal analysis and retail demand forecasting.

## Worth Knowing
The guide highlights that LSTMs are the go-to fix for "memory loss" in deep networks, using their internal gating state to selectively forget or store information. If you're building the hands-on project, remember that the data must be standardized between 0 and 1 before hitting the LSTM layer to ensure the math doesn't break.

---

## HOW TO - Google Colab RevFinal.pdf `PDF`

[Gemini error: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}]

---

## HOW TO - Usando GPU no Colab RevFinal.pdf `PDF`

[Gemini error: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}]

---
