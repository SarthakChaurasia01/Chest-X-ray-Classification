# Chest X-ray Classification using MobileNetV2

A deep learning image classification project that classifies chest X-ray images into three categories:

- Normal
- COVID-19
- Pneumonia

The project uses transfer learning with MobileNetV2 pretrained on ImageNet.

## Overview

Chest X-ray classification is a computer vision problem involving the identification of visual patterns associated with different lung conditions.

This project explores the use of convolutional neural networks and transfer learning to classify chest X-ray images into three predefined classes.

The workflow includes:

1. Image preprocessing
2. Data augmentation
3. Transfer learning using MobileNetV2
4. Model training
5. Fine-tuning
6. Model evaluation
7. Confusion matrix and classification report analysis

## Dataset

The project uses a labeled chest X-ray dataset containing three classes:

- Normal
- COVID-19
- Pneumonia

Dataset source:

[Insert the exact dataset source used for this project]

### Dataset Distribution

| Class | Images |
|---|---:|
| Normal | XX |
| COVID-19 | XX |
| Pneumonia | XX |
| Total | XX |

## Methodology

### Preprocessing

The images were:

- Resized to the required input dimensions
- Normalized
- Organized into the three target classes

### Data Augmentation

Training images were augmented to improve model generalization.

The augmentation pipeline included the transformations used in the training notebook.

### Transfer Learning

MobileNetV2 pretrained on ImageNet was used as the base feature extractor.

The classification head was adapted for the three target classes.

### Fine-tuning

Selected layers of the pretrained network were fine-tuned after initial training.

### Training

The model was trained using:

- Optimizer: [actual optimizer]
- Loss function: [actual loss]
- Batch size: [actual batch size]
- Epochs: [actual epochs]
- Input size: [actual image dimensions]

## Results

The model achieved a validation accuracy of **96.5%** in the reported experiment.

| Metric | Score |
|---|---:|
| Validation Accuracy | 96.5% |
| Precision | XX |
| Recall | XX |
| F1 Score | XX |

Additional evaluation includes:

- Confusion matrix
- Classification report
- Training and validation curves

## Model Architecture

```text
Input Image
     |
     v
Image Preprocessing
     |
     v
MobileNetV2
(pretrained on ImageNet)
     |
     v
Global Average Pooling
     |
     v
Classification Head
     |
     v
3 Output Classes
Normal / COVID-19 / Pneumonia
