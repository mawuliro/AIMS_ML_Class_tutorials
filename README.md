<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║    ███╗   ███╗ █████╗  ██████╗██╗  ██╗██╗███╗   ██╗███████╗    ║
║    ████╗ ████║██╔══██╗██╔════╝██║  ██║██║████╗  ██║██╔════╝    ║
║    ██╔████╔██║███████║██║     ███████║██║██╔██╗ ██║█████╗      ║
║    ██║╚██╔╝██║██╔══██║██║     ██╔══██║██║██║╚██╗██║██╔══╝      ║
║    ██║ ╚═╝ ██║██║  ██║╚██████╗██║  ██║██║██║ ╚████║███████╗    ║
║    ╚═╝     ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚═╝╚═╝  ╚═══╝╚══════╝   ║
║                                                                  ║
║                    L E A R N I N G                               ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

# ⚡ ML FROM SCRATCH · AIMS GHANA 2025

*Because the best way to understand a machine is to build one.*

[![Python](https://img.shields.io/badge/Python-3.8+-FFD43B?style=flat-square&logo=python&logoColor=black)](https://python.org)
[![NumPy](https://img.shields.io/badge/NumPy-Only-013243?style=flat-square&logo=numpy)](https://numpy.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org)
[![AIMS Ghana](https://img.shields.io/badge/AIMS-Ghana_2025-006B3F?style=flat-square)](https://aims.edu.gh)
[![License](https://img.shields.io/badge/License-MIT-A8FF78?style=flat-square)](#-license)

</div>

---

<div align="center">

> *"In theory, theory and practice are the same. In practice, they are not."*
> — Every ML student, ever.

</div>

---

## 🌍 The Story

These notebooks were born in **Accra, Ghana**, inside the walls of the African Institute for Mathematical Sciences. Six notebooks. Two assignments. Four tutorials. One goal: understand machine learning **from the ground up** — not as a black box, but as mathematics you can hold in your hands.

No shortcuts. No `sklearn.fit()` without knowing what *fit* actually means first.

**Author →** Mawulikplimi Roland Hounkpe &nbsp;·&nbsp; `rhounkpe`

---

## 🗺️ The Map

```
aims-ml-2025/
│
├── 📝  Assignment_1_Linear_Regression.ipynb
├── 📝  Assignment_2_Polynomial_Gaussian_Regression.ipynb
│
├── 📚  Tutorial_2_Classification_with_sklearn.ipynb
├── 📚  Tutorial_3_KMeans_and_PCA.ipynb
├── 📚  Tutorial_4_Polynomial_and_RBF_Regression.ipynb
└── 📚  Tutorial_5_Five_ML_Algorithms_From_Scratch.ipynb
```

---

## 📖 The Notebooks

### `Assignment_1` &nbsp;·&nbsp; 📐 Linear Regression

> *Start at zero. Derive everything.*

The first assignment strips linear regression down to its bones. We derive the optimal parameters three different ways — because if you can only solve a problem one way, you don't really understand it.

```
What's inside ──────────────────────────────────────────────────
  ∂ℓ/∂θ = 0    →   Closed-form analytical derivation
  (XᵀX)⁻¹Xᵀy  →   Normal equation (matrix magic)
  θ ← θ - α∇ℓ  →   Gradient descent + convergence analysis
  🏔️             →   3D loss surface + contour + GD trajectory
  📏             →   Feature normalisation & the Olympic dataset
─────────────────────────────────────────────────────────────────
```

---

### `Assignment_2` &nbsp;·&nbsp; 🌊 Polynomial & Gaussian Regression

> *When a line isn't enough.*

Reality is rarely linear. This assignment explores what happens when we give our model richer features — and what goes wrong when we give it too many.

```
What's inside ──────────────────────────────────────────────────
  x, x², x³…   →   Polynomial basis + Vandermonde design matrix
  📉 📈          →   Bias-variance trade-off visualised
  🔁             →   5-Fold cross-validation for model selection
  λ‖θ‖²         →   Ridge regularisation — taming the beast
  🔔             →   Gaussian basis functions + bandwidth analysis
  🎯             →   Radial Basis Functions (RBF) regression
─────────────────────────────────────────────────────────────────
```

---

### `Tutorial_2` &nbsp;·&nbsp; ⚔️ Classification Battle — sklearn Edition

> *Four algorithms walk into a classroom. Only one wins.*

A head-to-head tournament between four classifiers on real exam data. The arena: who gets admitted? The judges: decision boundaries, probabilities, and cross-validated accuracy.

| Classifier | Boundary Shape | Secret Weapon |
|:---|:---:|:---|
| 🔵 Logistic Regression | Linear | Probability estimates |
| 🟠 SVM | Non-linear | Maximum margin |
| 🟢 K-Nearest Neighbours | Voronoi | No training needed |
| 🔴 Decision Tree | Axis-aligned | Human-readable rules |

---

### `Tutorial_3` &nbsp;·&nbsp; 🎨 K-Means + PCA — Unsupervised Minds

> *Find the pattern. No one told you what to look for.*

Two algorithms that learn without labels — one groups, one compresses.

```
K-MEANS ────────────────────────────────────────────────────────
  🔵🔴🟢   →   Cluster 2D points from scratch
  🖼️        →   Compress a photo from 16M colours → 16 colours
              (it still looks like a bird)

PCA ────────────────────────────────────────────────────────────
  λ, v      →   Eigendecomposition by hand
  📊        →   Project high-dim data, recover with sklearn
  🔬        →   Side-by-side: scratch vs. scikit-learn
─────────────────────────────────────────────────────────────────
```

---

### `Tutorial_4` &nbsp;·&nbsp; 🌀 Polynomial & RBF Regression

> *Give the model the right eyes.*

Basis functions change *how* the model sees the data. Polynomials look globally. Gaussians look locally. Both are linear regression — just in disguise.

- Vandermonde design matrices · multiple degree comparison
- Gaussian RBF with random centres · bandwidth effects
- Normal Equation throughout — no gradient descent needed

---

### `Tutorial_5` &nbsp;·&nbsp; 🏗️ Five Algorithms. Zero Libraries.

> *The magnum opus.*

The most complete notebook. Five fundamental algorithms, each built entirely with NumPy — from the math on paper to a working, tested implementation.

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  01 ── LINEAR REGRESSION        Normal eq. + gradient descent
  02 ── POLYNOMIAL REGRESSION    Feature mapping, degree 6
  03 ── LOGISTIC REGRESSION      Sigmoid + cross-entropy + boundary
  04 ── K-NEAREST NEIGHBOURS     Distance + majority vote + k study
  05 ── LINEAR SVM               Hinge loss + margin maximisation
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  ✦  Decision boundaries for every classifier
  ✦  Final accuracy shootout on held-out test set
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 🧩 Concepts × Notebooks

|  | A1 | A2 | T2 | T3 | T4 | T5 |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|
| Normal Equation | ✅ | ✅ | | | ✅ | ✅ |
| Gradient Descent | ✅ | ✅ | | | | ✅ |
| Bias-Variance | | ✅ | | | | |
| Cross-Validation | | ✅ | ✅ | | | ✅ |
| Regularisation (L2) | | ✅ | | | | |
| Logistic Regression | | | ✅ | | | ✅ |
| SVM | | | ✅ | | | ✅ |
| KNN | | | ✅ | | | ✅ |
| Decision Tree | | | ✅ | | | |
| K-Means | | | | ✅ | | |
| PCA | | | | ✅ | | |
| Basis Functions | | ✅ | | | ✅ | |

---

## 📦 Setup

```bash
# 1. Clone
git clone https://github.com/<your-username>/aims-ml-2025.git
cd aims-ml-2025

# 2. Install
pip install numpy pandas matplotlib scipy scikit-learn jupyter

# 3. Launch
jupyter notebook
```

> **Data files** (`linearReg.out`, `gabor_data.out`, `ex2data1.txt`, `kmeans_data.mat`, `bird_small.png`, etc.) are provided by the course. Place them in the same directory as the notebooks.

---

## 🌐 Stack

```
Language  ──  Python 3.8+
Core      ──  NumPy · Pandas · Matplotlib · SciPy
ML lib    ──  scikit-learn  (tutorials only — assignments use scratch)
Platform  ──  Jupyter Notebook
```

---

## 📜 License

MIT — use it, learn from it, build on it. Just keep the spirit alive.

---

<div align="center">

```
┌─────────────────────────────────────────────────┐
│                                                 │
│   Built with curiosity at AIMS Ghana · 2025    │
│   Accra · Mathematics · Machine Learning       │
│                                                 │
└─────────────────────────────────────────────────┘
```

*"The purpose of computing is insight, not numbers."*
— Richard Hamming

</div>