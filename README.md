# 🥔 Potato Leaf Classifier 🌿

A deep learning-based image classification model to detect **healthy** and **diseased** potato leaves using Convolutional Neural Networks (CNNs).

---

## 📌 Project Overview

This project aims to assist farmers and researchers by providing an accurate and automated solution for classifying potato leaf images into:

- ✅ **Healthy**
- ❌ **Diseased**

The classifier is trained on a labeled dataset of potato leaf images using a custom CNN architecture or transfer learning models (e.g., ResNet, VGG).

---

## 🧠 Model Highlights

- 📦 **Framework**: Python, TensorFlow/Keras (or PyTorch)
- 🧑‍🌾 **Application**: Agricultural disease detection
- 🧪 **Model Type**: 2D CNN / Transfer Learning
- 🖼️ **Input**: Leaf images (JPG/PNG)
- 🧾 **Output**: Predicted label - *Healthy* or *Diseased*

---

## 📁 Dataset

- Source: [PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
- Classes: 
  - Potato___Early_blight
  - Potato___Late_blight
  - Potato___Healthy
- Preprocessing:
  - Image resizing
  - Normalization
  - Data augmentation (rotation, flip, zoom)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/potato-leaf-classifier.git
cd potato-leaf-classifier
