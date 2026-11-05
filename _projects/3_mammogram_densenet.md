---
layout: page
title: Two-Stage Multi-View DenseNet121 for Mammogram Classification
description: A two-stage pipeline that mirrors the radiologist workflow on VinDr-Mammo.
img:
importance: 3
category: imaging
---

I built a two-stage multi-view DenseNet121 pipeline on VinDr-Mammo (4,750 studies, 9,499 paired CC/MLO breast samples) that mirrors the radiologist workflow:

- **Stage 1** screens normal (BI-RADS 1) vs. abnormal (2–6).
- **Stage 2** separates benign (2–3) from suspicious or malignant findings (4–6).

I compared ResNet, DenseNet, VGG, and ViT, trained on a 50/50 undersampled set, and tested on natural-distribution held-out sets (1,426 and 470 samples). Stage 1 reached 62.6% sensitivity (F1 0.563) and Stage 2 reached 50.7% sensitivity (F1 0.455).

**Stack:** Python, PyTorch, medical imaging.

[Code on GitHub](https://github.com/ToobaMir/Densenet-for-Mammogram-Classification)
