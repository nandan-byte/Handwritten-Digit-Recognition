# 🧠 Handwritten Digit Recognition using Perceptron, ANN & CNN

This project focuses on classifying handwritten digits (0–9) from the MNIST dataset using three deep learning architectures — Perceptron, Artificial Neural Network (ANN), and Convolutional Neural Network (CNN).  
The aim is to analyze how model depth and architecture impact performance and accuracy.

---

## 📊 Dataset
- **Dataset Used:** MNIST Handwritten Digits  
- **Description:** The dataset contains 70,000 grayscale images of handwritten digits (0–9), each of size 28×28 pixels.  
- **Training Samples:** 60,000  
- **Testing Samples:** 10,000  

---

## 🧩 Models Overview
### Perceptron  
A simple single-layer neural network used as a baseline model. It performs linear classification but struggles with complex non-linear patterns.

### Artificial Neural Network (ANN)  
A multi-layer perceptron (MLP) that learns non-linear representations using activation functions like ReLU. It achieves significantly higher accuracy than the Perceptron.

### Convolutional Neural Network (CNN)  
A deep learning architecture specifically designed for image data. It uses convolution and pooling layers for spatial feature extraction and includes dropout to prevent overfitting. CNN achieved the highest accuracy among all models.

---

## ⚙️ Technologies Used
- **Programming Language:** Python  
- **Frameworks & Libraries:** TensorFlow, Keras, NumPy, Matplotlib, scikit-learn  

---

## 📈 Model Performance (Approx.)
| Model | Accuracy | Key Notes |
|--------|-----------|-----------|
| Perceptron | ~91% | Linear model, baseline |
| ANN | ~97% | Learns non-linear patterns |
| CNN | ~99% | Best performing model |

> Accuracy values may slightly vary depending on training parameters and environment.

---
