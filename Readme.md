# 🧠 Federated Learning-based Lung Disease Prediction using Heterogeneous Data

A major project developed using **Federated Learning (FL)** integrated with **Convolutional Neural Networks (CNN)**, **Support Vector Machine (SVM)**, and **Random Forest (RF)** for predicting lung diseases such as **COVID-19** and **Pneumonia** using **Chest X-ray** and **CT-Scan** images.

---

## 📌 Abstract

Lung diseases like COVID-19 and Pneumonia require fast and accurate diagnosis. In this project, we used **Federated Learning** to train models on decentralized medical data, preserving privacy and security. We processed **heterogeneous image data** (CT and X-ray) and applied combinations like PCA + CNN, PCA + CNN + SVM, and PCA + CNN + RF.

> ✅ **Best Accuracy: 98.33% using PCA + CNN + SVM**

---

## 🛠️ Tech Stack

- **Language**: Python
- **Frameworks & Libraries**:  
  - TensorFlow  
  - Scikit-learn  
  - OpenCV  
  - NumPy  
  - Matplotlib  
- **Techniques**:  
  - Federated Learning (FedAvg)  
  - PCA for dimensionality reduction  
  - CNN for feature extraction  
  - SVM & Random Forest for classification

---

## 📁 Dataset

- **Classes**: COVID-19, Pneumonia, Normal
- **Image Types**: Chest X-ray and CT-Scan
- **Image Dimensions**: 224x224 pixels  
- **Total Images**: 1200 (400 per class; 200 X-ray + 200 CT for each)

---

## 🔄 Methodology

- Preprocess images (resize, grayscale, normalize)
- Apply PCA to reduce dimensions
- Implement CNN for feature extraction
- Train models using Federated Learning across multiple clients
- Aggregate weights with **FedAvg**
- Compare CNN, CNN+SVM, and CNN+RF models

---

## 📊 Results

| Model Combination       | Accuracy |
|-------------------------|----------|
| PCA + CNN               | 96.67%   |
| PCA + CNN + RF          | 97.50%   |
| PCA + CNN + SVM         | 98.33% ✅ |

