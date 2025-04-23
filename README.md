# 🧠 Machine Learning Models with PyTorch

This repository contains three progressively complex PyTorch-based classification models. Each demonstrates a different approach — from manual training loops to modular `nn.Module` structures — showcasing the evolution of model-building skills.

---

## 📂 Repository Navigation

```
Machine-Learning-Models/
│
├── 01_pytorch_workflow.ipynb       # Manual binary classification with raw tensors
├── 02_MCM.ipynb                    # Manual multi-class classification using softmax and CE loss
├── 02_neural_networks.ipynb        # nn.Module-based binary classifier using BCEWithLogitsLoss
└── README.md                       # Project documentation (this file)
```

---

## 🚀 Models Overview & Results

### 🔹 Model 1 — `01_pytorch_workflow.ipynb`
- **Type**: Binary Classification (Manual)
- **Loss**: `Binary Cross Entropy (BCE)`
- **Optimizer**: Manual Gradient Descent
- **Final Accuracy**: ~95%
- **Final Loss**: ~0.05

### 🔹 Model 2 — `02_MCM.ipynb`
- **Type**: Multi-Class Classification (Manual)
- **Loss**: `CrossEntropyLoss`
- **Optimizer**: `SGD`
- **Final Accuracy**: ~92%
- **Final Loss**: ~0.18

### 🔹 Model 3 — `02_neural_networks.ipynb`
- **Type**: Binary Classification (Modular)
- **Loss**: `BCEWithLogitsLoss`
- **Optimizer**: `SGD (lr=0.01)`
- **Final Accuracy**: ~97%
- **Final Loss**: ~0.03

> _Note: Metrics may slightly vary depending on seed and hardware._

---

## 🧰 Features

- ✅ Manual & modular PyTorch models
- ✅ Custom training/evaluation loops
- ✅ Accuracy monitoring and loss tracking
- ✅ GPU-compatible
- ✅ Educational structure for beginners

---

## 🔧 Requirements

```bash
pip install torch torchvision matplotlib tqdm
```

---

## 📈 Planned Improvements

- [ ] Add training visualizations
- [ ] Export `.pt` models for reuse
- [ ] Add CNN support for image classification
- [ ] Improve modularity with `train()` and `test()` functions

---

## 👨‍💻 Author

**Aryan Shukla**  
BTech Software Engineering @ DTU  
🧠 Machine Learning • 🕸️ Web Dev • ⚙️ Systems Programming

---

## ⭐ Project Rating

**🔍 Current Score**: 8.5 / 10  
✅ Great modular structure  
✅ Clearly evolving complexity  
⚠️ Missing visualizations and docstrings  

Feel free to ⭐ star the repo or open a PR to contribute!

---

## 📬 Questions / Contributions

Open an issue or contact me through GitHub for collaboration ideas or feedback.