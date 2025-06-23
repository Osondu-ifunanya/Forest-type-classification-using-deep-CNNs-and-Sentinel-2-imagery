# 🌲 Forest Type Classification using Deep CNNs and Synthetic Sentinel-2 Imagery

## 📘 Overview

This project demonstrates how to classify forest types (Tropical, Temperate, Boreal) using Deep Convolutional Neural Networks (CNNs) applied to synthetic Sentinel-2-like image patches. The images simulate four spectral bands: Red, Green, Blue, and Near-Infrared (NIR).

---

## 📁 Dataset

The dataset contains **1,500 synthetic image samples** of size 64×64 pixels with 4 channels (RGB + NIR). The data are grouped into:

- **Tropical forests**: High NIR and Green reflectance
- **Temperate forests**: Balanced spectral response
- **Boreal forests**: Lower NIR, slightly higher Red

📄 A simplified dataset containing the mean reflectance values for each band is also provided:
[Download synthetic_forest_classification_data.xlsx](./synthetic_forest_classification_data.xlsx)

---

## 🧪 Features

- Synthetic remote sensing image simulation
- Deep CNN model for image classification
- Multi-class forest type prediction
- Model evaluation using accuracy and confusion matrix
- Training history visualization

---

## 🛠 Tools Used

- Python 3.8+
- NumPy
- Pandas
- TensorFlow / Keras
- Scikit-learn
- Matplotlib

---

## 🚀 How to Run

1. **Install dependencies**
   ```bash
   pip install numpy pandas tensorflow scikit-learn matplotlib
