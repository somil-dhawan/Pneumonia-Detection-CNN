# Pneumonia-Detection-CNN
Convolutional Neural Network designed to detect pneumonia using X-Ray images.


## 📌 Problem

Pneumonia is a serious lung infection that requires early diagnosis. 
Manual analysis of chest X-rays is time-consuming and prone to error.

This project aims to build a deep learning model that can automatically 
detect pneumonia from chest X-ray images.

## 🎯 Objective

- Classify chest X-ray images as:
  - Pneumonia
  - Normal
- Build an efficient and accurate deep learning pipeline
- Analyze model performance using proper evaluation metrics

- ## 📂 Dataset

- Source: Kaggle Chest X-ray Dataset
- Structure:
  - train/
  - val/
  - test/

The dataset contains labeled X-ray images for pneumonia and normal cases.

## ⚙️ Methodology

- Used transfer learning with ResNet18
- Applied data preprocessing and augmentation
- Trained using PyTorch
- Fine-tuned deeper layers for improved performance

- ## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score

In medical diagnosis, recall is especially important to minimize false negatives.
