
# 📘 DALab Project

This repository contains the implementation and experiments for a project inspired by non-parametric representation learning using kernels. The notebook primarily explores **Contrastive Kernel Learning** (CKL) for representation learning and evaluates its performance through kernel-based transformations and downstream KNN classification.

## 🧠 Project Summary

The project is motivated by recent works such as *"Nonparametric Representation Learning with Kernels"* (Esser et al., 2023), which challenge the dominance of deep neural networks in representation learning by proposing kernel-based methods with theoretical guarantees.

In this project, we:
- Implement **Spectral Kernel Learning (SKL)** and **Contrastive Kernel Learning (CKL)**.
- Use **RBF kernels** and **kernel inversion** techniques to project data into meaningful embeddings.
- Evaluate performance using KNN classifiers on datasets like MNIST and IRIS.

## 📁 Project Structure

```
dalabproject.ipynb     # Main notebook containing SKL and CKL implementations, visualizations, and experiments.
requirements.txt       # Dependencies required to run the notebook.
README.md              # Project overview, setup, and usage instructions.

```

## 🔧 Setup Instructions

Install the required packages using:
```bash
pip install -r requirements.txt
```

You will need Python 3.8+, and a GPU is recommended for kernel inversion and faster matrix computations.

## 🧪 How to Run

### ⚠️ IMPORTANT INSTRUCTIONS

Please follow these steps **before running the notebook**:

1. Please load **Iris dataset** (`.csv`) and **MNIST dataset** (`.mat`) in your working directory.

2. Open the notebook and set the correct path for the variable `path` where indicated.

3. Un-comment the code block for the dataset you want to run (`Iris` or `MNIST`).

4. **Run the notebook**:

   ```bash
   jupyter notebook dalabproject.ipynb

5. Follow the cells sequentially.

## 📊 Results

- Vanilla KNN (baseline)
- PCA + KNN
- Kernel PCA + KNN
– Kernel Autoencoders + KNN
– Spectral contrastive kernel learning)
– Simple contrastive kernel learning)

## 📚 References

- Esser, P., et al. (2023). *Nonparametric Representation Learning with Kernels*. arXiv:2305.13454.
- Related work in contrastive learning and kernel methods

## 🧑‍🔬 Author

Anushka Chaubey  
For Data Analytics Lab Coursework @IITM, 2025
