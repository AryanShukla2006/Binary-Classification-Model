# 🧠 Machine Learning Models using PyTorch

A collection of PyTorch-based implementations for binary classification tasks. This repository demonstrates the end-to-end workflow of building, training, and evaluating deep learning models using PyTorch.

## 📁 Repository Structure

- `01_pytorch_workflow.ipynb` — Basic training workflow using PyTorch
- `02_MCM.ipynb` — Custom model with manual training loop
- `02_neural_networks.ipynb` — Neural network with `nn.Module` structure
- `README.md` — Project overview

## 🚀 Project Highlights

- Built with **PyTorch**
- Uses `BCELoss` / `BCEWithLogitsLoss` for binary classification
- Trained using **SGD** optimizer
- Clean training & evaluation loop with accuracy tracking
- Easily extendable for more complex models and datasets

## 🛠️ Features

- Input data preprocessing
- Model definition using `nn.Module`
- Forward and backward pass
- Manual training loop with metric logging
- GPU-compatible structure (easily switch `device`)

## 📈 Results

Model achieves stable convergence on synthetic/binary classification tasks with optimized loss and validation accuracy.

## ✅ Dependencies

- Python 3.8+
- PyTorch
- NumPy
- Matplotlib
- tqdm

Install dependencies:
```bash
pip install -r requirements.txt
