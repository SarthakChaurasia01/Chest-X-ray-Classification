# Chest X-ray Classification using MobileNetV2

A deep learning project to classify chest X-ray images into three categories: **Normal**, **COVID-19**, and **Pneumonia**, using transfer learning with **MobileNetV2**.

![model-preview](https://user-images.githubusercontent.com/your-image-path/preview.png) <!-- Optional: Replace with actual image link -->

## 🧠 Overview

This project applies convolutional neural networks (CNNs) and transfer learning on chest X-ray datasets to automatically detect and differentiate between:
- Healthy lungs (Normal)
- COVID-19 infections
- Pneumonia infections

---

## 📁 Dataset

The dataset used includes labeled chest X-ray images categorized into:
- `Normal`
- `COVID-19`
- `Pneumonia`

Sources:
- COVID-19 Radiography Dataset (Kaggle)
- ChestX-ray8 Dataset (NIH)

> Ensure that data is properly cleaned and resized to (224, 224, 3) before training.

---

## 🛠️ Tech Stack & Libraries

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- MobileNetV2 (pretrained on ImageNet)

---

## 🚀 Features

- ✅ Image Preprocessing & Augmentation
- ✅ Transfer Learning with MobileNetV2
- ✅ Fine-tuning CNN layers
- ✅ Early stopping & model checkpointing
- ✅ Training and validation accuracy/loss visualization
- ✅ Confusion Matrix and Classification Report

---

## 📊 Results

- Achieved over **96.5%** accuracy on the validation set.
- High precision & recall in COVID-19 class detection.
- Visualized training curves and confusion matrix.

