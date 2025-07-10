# MNIST Neural Network from Scratch (Kaggle Notebook)

A simple, fully‑connected 2‑layer neural network built from scratch using NumPy — developed and trained entirely in a Kaggle Notebook to classify handwritten digits from the MNIST dataset.

## 📌 Overview

- **No deep learning libraries** — built with pure NumPy
- Implements forward propagation, backpropagation, and gradient descent
- Utilizes ReLU activation in the hidden layer and Softmax in the output layer
- Trained on the MNIST dataset (from Kaggle)

## 🔧 Environment

- ✅ Run inside [Kaggle Notebooks](https://www.kaggle.com/code)
- 📦 Dependencies:
  - Python 3.x
  - NumPy
  - Pandas
  - Matplotlib (optional, for visualizations)

## 🗃 Dataset

- MNIST Digit Recognizer dataset from Kaggle:
  - 📥 [https://www.kaggle.com/datasets/animatronbot/mnist-digit-recognizer](https://www.kaggle.com/datasets/animatronbot/mnist-digit-recognizer)

## 🧠 Neural Network Architecture

- **Input Layer**: 784 neurons (28×28 pixel images)
- **Hidden Layer**: 10 neurons, ReLU activation
- **Output Layer**: 10 neurons (digits 0–9), Softmax activation
