# 🌭 Hot Dog Or Not Hot Dog

> Binary image classifier built with a CNN — inspired by the Silicon Valley TV show

---

## 🎯 Project Overview

Can a neural network tell if a food image contains a hot dog or not?  
This project builds a **Convolutional Neural Network (CNN)** trained on the Food-101 
dataset to solve this fun but technically rich binary classification problem.

---

## 🧠 Model Architecture

| Layer | Details |
|---|---|
| Input | 128x128 RGB images |
| Conv2D x3 | 32 → 64 → 128 filters + ReLU |
| MaxPooling | After each Conv block |
| Dropout | Regularization to reduce overfitting |
| L2 Regularization | Weight penalty on Conv layers |
| Dense Output | Sigmoid activation (binary) |

---

## 📊 Dataset

- **Source:** Food-101 via TensorFlow Datasets
- **Total images:** 75,000+
- **Class imbalance fix:** Oversampling hot dog class (x3)
- **Data augmentation:** Random horizontal flip + rotation

---

## ⚙️ Training

- **Epochs:** 50
- **Optimizer:** Adam
- **Loss:** Binary Crossentropy

---

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square)

---
