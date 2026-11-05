---
layout: page
title: "Cell Analysis in R: From Gene Data to Machine Learning"
description: Single-cell RNA-seq clustering and kNN classification of PBMCs (BIO312 course project).
img:
importance: 4
category: genomics
---

I analyzed 10x Genomics PBMC 1k scRNA-seq data with Seurat (normalization, 2,000 highly variable genes, PCA, UMAP) and identified 8 cell clusters, assigning T-cell (CD3D), B-cell (MS4A1), and monocyte-like (VCAN) populations via marker genes.

I then trained a kNN classifier (caret) on PCA features using a stratified 70/30 split, reaching 96.82% accuracy (κ = 0.96) on 220 held-out cells.

**Stack:** R, Seurat, caret, kNN.

[Code on GitHub](https://github.com/ToobaMir/R-Project)
