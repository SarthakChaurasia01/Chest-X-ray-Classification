# Chest X-ray Classification using MobileNetV2

A deep learning project for classifying chest X-ray images into three categories:

**Normal · COVID-19 · Pneumonia**

Built using TensorFlow/Keras and MobileNetV2 transfer learning.

<p align="center">
  <a href="notebook/Chest-X-Ray-Classification.ipynb">
    <img src="https://img.shields.io/badge/View-Notebook-1f6feb?style=for-the-badge" alt="View Notebook">
  </a>
  <a href="https://www.kaggle.com/datasets/prashant268/chest-xray-covid19-pneumonia">
    <img src="https://img.shields.io/badge/Dataset-Kaggle-20beff?style=for-the-badge" alt="Dataset">
  </a>
</p>

---

## Overview

This project uses transfer learning with **MobileNetV2**, a pretrained convolutional neural network, to classify chest X-ray images into three classes:

- Normal
- COVID-19
- Pneumonia

The project covers image preprocessing, model training, evaluation, and visual analysis of predictions.

---

## Model Architecture

The classification pipeline follows:

```text
Chest X-ray Image
        ↓
Image Preprocessing
        ↓
MobileNetV2
(Pretrained on ImageNet)
        ↓
Global Average Pooling
        ↓
Dense Classification Layer
        ↓
Normal / COVID-19 / Pneumonia
