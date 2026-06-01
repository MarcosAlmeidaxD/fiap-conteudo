# HOW TO - Usando GPU no Colab RevFinal.pdf

**File type:** PDF | **Processed:** 2026-06-01

## TL;DR
Quick guide for swapping the default Colab CPU for a T4 GPU to speed up model training.

## What's Inside
- **UI Navigation:** Click `Connect` > `Change runtime type` > Select `T4 GPU`.
- **Hardware Specs:** Provisioning a GPU environment with approximately 12GB of VRAM.
- **Destructive Reset:** Warning that switching hardware kills the current session and wipes all local variables/temporary files.
- **Explicit Execution:** TensorFlow snippet `with tf.device("/device:GPU:0"):` to force specific code blocks onto the GPU.

## Worth Knowing
Because the environment starts completely "clean" after the swap, you must re-run all setup cells and re-upload any local data files every time you toggle the hardware accelerator.
