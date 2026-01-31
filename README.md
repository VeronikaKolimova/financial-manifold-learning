# 📊 Financial Manifold Learning / Сравнение алгоритмов снижения размерности на данных NYSE

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-green)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/financial-manifold-learning/blob/main/Lab_04_son_release.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/your-username/financial-manifold-learning/HEAD?labpath=Lab_04_son_release.ipynb)

**EN:** Comparative study of manifold learning techniques (MDS, t-SNE, UMAP, ISOMAP, LLE) applied to NYSE financial data.

**RU:** Сравнительное исследование методов снижения размерности (MDS, t-SNE, UMAP, ISOMAP, LLE) на данных NYSE.



## 🚀 Quick Start / Быстрый старт

###  Local Installation / Локальная установка

```bash
# Clone repository
git clone https://github.com/your-username/financial-manifold-learning.git
cd financial-manifold-learning

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```
A comprehensive machine learning project exploring dimensionality reduction techniques applied to NYSE financial data. This repository demonstrates how to transform high-dimensional financial metrics into 2D/3D visualizations using various manifold learning algorithms.

## Features
- Data preprocessing pipeline for financial datasets
- Implementation of 5 dimensionality reduction methods:
  - MDS (Multidimensional Scaling)
  - ISOMAP
  - LLE (Locally Linear Embedding)
  - t-SNE (t-Distributed Stochastic Neighbor Embedding)
  - UMAP (Uniform Manifold Approximation and Projection)
- Interactive visualization of financial clusters
- Comparative analysis of different algorithms

## Technologies
- Python 3.8+
- scikit-learn, UMAP-learn
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook

## Use Cases
- Exploratory data analysis of financial markets
- Comparative study of dimensionality reduction techniques
- Educational resource for manifold learning
- Template for financial data visualization projects
