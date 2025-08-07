# 🧠 MNIST Digit Classification with Neural Networks

This project demonstrates a simple but powerful neural network built using TensorFlow/Keras to classify handwritten digits from the famous **MNIST dataset**.

---

## 📊 Dataset

- **Source**: [MNIST](http://yann.lecun.com/exdb/mnist/)
- **Images**: 70,000 grayscale images (28x28 pixels)
  - 60,000 for training
  - 10,000 for testing
- **Labels**: Digits from 0 to 9

---

## 🚀 Model Overview

- **Architecture**:
  - Input Layer: 784 neurons (28x28 flattened)
  - Hidden Layers:
    - Dense(128) + ReLU
    - Dropout(0.2)
    - Dense(64) + ReLU
  - Output Layer: Dense(10) + Softmax
- **Loss**: Sparse Categorical Crossentropy
- **Optimizer**: Adam
- **Accuracy**: ~98% on test set

---

## 🛠️ Technologies Used

- Python 🐍
- TensorFlow / Keras 📦
- NumPy 📐
- Matplotlib 📊
- Google Colab 💻

---

## 📁 Project Structure

