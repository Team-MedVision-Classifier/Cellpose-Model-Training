
# Cellpose 3.1.1  Model Fine-Tuning Results

## Overview

This repository contains the fine-tuning results of the **Cellpose v3.1.1** model for microscopy image segmentation. The objective of this work is to adapt a pretrained Cellpose model to domain-specific biological data in order to improve segmentation performance.

---

## Data

The dataset used in this project consists of microscopy images with corresponding segmentation annotations.

- **Image type:** Microscopy images  
- **Segmentation tasks:**
  - Cell segmentation
- **Annotation format:** NumPy (`.npy`) segmentation masks  
- **Data splits:**
  - Training
  - Testing


---

## Training

Fine-tuning was performed using **Cellpose version 3.1.1**, initialized from pretrained model weights.

- **Framework:** Cellpose v3.1.1  
- **Training method:** Supervised fine-tuning  
- **Experiment setup:**
  - Multiple configurations (e.g., learning rates)  
  - Results organized by experiment folders  
- **Hardware:** GPU-accelerated training where available  

All training configurations and outputs are preserved to support comparison across experiments.

---

## Results

This repository includes fine-tuning outputs such as:

- Predicted segmentation masks
- Test set evaluation results

The results can be used to:
- Evaluate segmentation quality
- Compare fine-tuned models against baseline Cellpose performance

---

## Notes

- This is a **public research repository** provided for transparency and reproducibility.
- Users should cite **Cellpose** when using or building upon this work.
- For training pipelines, inference scripts, and documentation, refer to the official Cellpose repository and documentation.

---
