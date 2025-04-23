# 🧠 Machine Learning Models with PyTorch

This repository demonstrates multiple machine learning model implementations using **PyTorch** for classification tasks, progressing from basic to structured neural networks.

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `01_pytorch_workflow.ipynb` | 🔹 A basic linear binary classifier built from scratch using only tensors and matrix operations. |
| `02_MCM.ipynb` | 🔹 Implements a Multi-Class Classification Model manually using PyTorch layers and custom loops. |
| `02_neural_networks.ipynb` | 🔹 A structured `nn.Module` based model for binary classification using `BCEWithLogitsLoss`. |

---

## 📌 Models Overview

### 1️⃣ Model 1 — `01_pytorch_workflow.ipynb`
- Manually built classifier without `nn.Module`
- Demonstrates basic understanding of weights, biases, loss, and gradient descent
- Implements custom training loop using only tensors
- Loss: `Binary Cross Entropy (BCE)`

### 2️⃣ Model 2 — `02_MCM.ipynb`
- A step-up in complexity: manually coded multiclass classification model
- Uses custom functions for accuracy, forward propagation, and evaluation
- Optimizer: SGD  
- Loss: `CrossEntropyLoss`

### 3️⃣ Model 3 — `02_neural_networks.ipynb`
- Fully modular implementation using `nn.Module`
- Suitable for binary classification tasks
- Loss: `BCEWithLogitsLoss`
- Optimizer: SGD
- Follows best practices (model encapsulation, `train()` and `eval()` modes)

---

## 🛠️ Features

- 📦 Built with **PyTorch**
- 🔁 Manual and modular training loops
- 📊 Accuracy tracking & loss monitoring
- 🔧 Easily adaptable to other datasets
- ⚡ GPU-compatible structure

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/AryanShukla2006/Machine-Learning-Models.git
   cd Machine-Learning-Models

