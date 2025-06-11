# 📊 SVM Visualizer - Make Moons Dataset

A Jupyter notebook project that demonstrates Support Vector Machine (SVM) classification using scikit-learn's make_moons dataset. This project visualizes how different SVM hyperparameters affect decision boundaries and model performance.

---
## 📑 Overview

This project creates visual comparisons of SVM models with different hyperparameter settings to help understand how gamma and C parameters influence classification results. The visualization shows decision boundaries and data points side-by-side for easy comparison.

---
## 📊 Features

- **Interactive Jupyter Notebook**: Step-by-step implementation and visualization
- **Multiple SVM Comparisons**: Compare 4 different hyperparameter combinations
- **Visual Decision Boundaries**: See how models separate different classes
- **Make Moons Dataset**: Uses scikit-learn's classic crescent-shaped dataset
- **RBF Kernel Implementation**: Demonstrates radial basis function kernel SVM

---
## 🛠️ Requirements

```python
matplotlib
scikit-learn
numpy
jupyter
```
---
## 🧪 Installation

1. Clone or download this repository
2. Install required packages:

```bash
pip install matplotlib scikit-learn numpy jupyter
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `make_moons_svm.ipynb`

---
## ⚗️ Usage

Run the notebook cells sequentially to:

1. Generate the make_moons dataset
2. Train SVM models with different hyperparameters:
   - gamma: 0.1 vs 5.0
   - C: 0.001 vs 1000
3. Visualize decision boundaries and compare results

---
## 🔮 Hyperparameter Combinations

The notebook compares four SVM models:

| Model | Gamma | C | Description |
|-------|-------|---|-------------|
| Model 1 | 0.1 | 0.001 | Low complexity, smooth boundary |
| Model 2 | 0.1 | 1000 | High regularization, smooth boundary |
| Model 3 | 5.0 | 0.001 | Low complexity, tight boundary |
| Model 4 | 5.0 | 1000 | High regularization, tight boundary |

---
## 🔧 Key Functions

- `plot_predictions()`: Visualizes SVM decision boundaries
- `plot_dataset()`: Displays data points with class colors
- SVM model training with RBF kernel
- 2x2 subplot comparison grid

---
## 📗 Learning Objectives

- Understand SVM hyperparameter effects
- Visualize decision boundaries
- Compare model performance visually
- Learn about overfitting vs underfitting in SVM

---
## 📊 Output

The main output is a 2x2 grid visualization showing:
- Decision boundaries (background colors)
- Training data points
- Model titles with hyperparameter values
- Side-by-side comparison for analysis

---
## 📂 File Structure

```
SVM Visualizer/
├── make_moons_svm.ipynb    # Main Jupyter notebook
└── README.md               # This file
```
---
## ✒️ Notes

- Ensure all notebook cells are run in order
- The visualization requires matplotlib backend support
- Dataset coordinates are set to `[-1.5, 2.45, -1, 1.5]` for consistent comparison
- Models must be trained before running the visualization code

---
⭐ If you found this project helpful, please consider giving it a star!