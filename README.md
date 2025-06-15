
# 📘 DALab Project

This repository contains the implementation and experiments for a project inspired by non-parametric representation learning using kernels. The notebook primarily explores **Contrastive Kernel Learning** (CKL) for representation learning and evaluates its performance through kernel-based transformations and downstream KNN classification.

## 🧠 Project Summary

The project is motivated by recent works such as *"Nonparametric Representation Learning with Kernels"* (Esser et al., 2023), which challenge the dominance of deep neural networks in representation learning by proposing kernel-based methods with theoretical guarantees.

In this project, we:
- Implement **Spectral Kernel Learning (SKL)** and **Contrastive Kernel Learning (CKL)**.
- Use **RBF kernels** and **kernel inversion** techniques to project data into meaningful embeddings.
- Evaluate performance using KNN classifiers on datasets like MNIST and CKPlus.

## 📁 Project Structure

```
dalabproject.ipynb     # Main notebook containing SKL and CKL implementations, visualizations, and experiments.
README.md              # Project overview, setup, and usage instructions.
```

## 🔧 Setup Instructions

You will need Python 3.8+ with the following libraries:

```bash
pip install numpy scipy scikit-learn matplotlib torch torchvision
```

Ensure GPU is available for faster kernel matrix inversion and large dataset processing.

## 🧪 How to Run

Open the notebook:

```bash
jupyter notebook dalabproject.ipynb
```

Follow the cells sequentially. The notebook is organized into:
1. **Data loading and preprocessing**
2. **Kernel matrix computation**
3. **Spectral or contrastive embedding**
4. **KNN classification and accuracy measurement**

## 📊 Results

- **SKL + KNN** outperforms raw data KNN on MNIST.
- Kernel-based methods show better class separation and generalization in low-dimensional embedding spaces.
- Visualizations of contrastive loss and kernel similarities demonstrate the effectiveness of CKL.

## 📚 References

- Esser, P., et al. (2023). *Nonparametric Representation Learning with Kernels*. arXiv:2305.13454.
- scikit-learn, PyTorch official docs
- Related work in contrastive learning and kernel methods

## 🧑‍🔬 Author

Anushka Chaubey  
For DaLab (Deep Artificial Intelligence Lab) Coursework, 2025
