# Pneumonia-Detection
Pneumonia detection from chest X-ray images using RestNet50 &amp; Grad-CAM

# Pneumonia Detection from Chest X-Rays

This project detects **Pneumonia** from chest X-ray images using **ResNet50 (transfer learning)** and provides explainability with **Grad-CAM heatmaps**.

---

## 📌 Overview
- **Dataset**: [Chest X-Ray Images (Pneumonia) - Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- **Model**: ResNet50 (ImageNet pretrained)
- **Framework**: TensorFlow / Keras
- **Test Accuracy**: 🚀 **64.47%** 
---

## 📊 Results
- Confusion Matrix & Classification Report included in notebook
- Grad-CAM highlights lung regions for pneumonia cases

Example Heatmap:

![Grad-CAM](assets/gradcam_example.png)

---

## 🛠️ How to Run
Open in Google Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/pneumonia-detection/blob/main/notebook.ipynb)

Steps:
1. Upload your `kaggle.json` (for dataset download).
2. Run all cells.

---

## ⚡ Requirements
See `requirements.txt`

