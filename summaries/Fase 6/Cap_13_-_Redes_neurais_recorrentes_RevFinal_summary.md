# Cap 13 - Redes neurais recorrentes RevFinal.pdf

**File type:** PDF | **Processed:** 2026-04-24

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
