# NLP Masters Project — Bayesian Evolution & Text Classification

This repository contains two self-contained Jupyter notebooks developed for a graduate-level NLP/ML course.  
It covers (1) a **Bayesian discrete evolution model** for longitudinal frequency data and (2) **text classification** (including a neural model) plus an **orthography modeling** mini-task.

---

## 📦 Repository Structure

```
.
├── bayesian_evolution.ipynb      # Bayesian discrete evolution & social dynamics
├── text_classification.ipynb     # Text classification & orthography modeling
└── Report.pdf                    # Written report (PDF)
```

---

## 🧠 Part 1 — Bayesian Discrete Evolution & Social Dynamics

**Notebook:** `bayesian_evolution.ipynb`

This notebook models how the frequency of a variant evolves over discrete time steps using **PyMC** for Bayesian inference and **ArviZ** for diagnostics/summary.  
A spline-based parameterization is used for components like *prevalence* and *imbalance*, and a separate *social dynamics* section explores age-group effects.

---

## 📝 Part 2 — Text Classification & Orthography Modeling

**Notebook:** `text_classification.ipynb`

This notebook includes two mini-projects:

1. **AI-Generated Text Classification**
   - Classical ML baseline using scikit-learn (Naive Bayes).
   - Neural baseline using PyTorch (feed-forward MLP).

2. **Orthography Modeling (character-level)**
   - Character-sequence based neural model for orthographic prediction.

---

## 🔧 Setup

Tested with **Python 3.10+**. Recommended installation:

```bash
python -m venv .venv
source .venv/bin/activate    # macOS/Linux
# .\.venv\Scripts\activate   # Windows

pip install numpy pandas matplotlib scipy scikit-learn torch pymc arviz jupyterlab
```

---

## ▶️ Quickstart

```bash
jupyter lab
```

Open and run:
- `bayesian_evolution.ipynb`
- `text_classification.ipynb`

---

## 📊 Results & Reporting

For detailed discussion, see the full report here:  
👉 [Report.pdf](https://github.com/Sohitha-01/NLP_masters_project/blob/e31c28f7153203e346c4970ff32b93255170801e/Report.pdf)

---

## 🙌 Acknowledgements
  
Author: Sohitha Kommineni.  
Libraries: NumPy, pandas, SciPy, Matplotlib, scikit-learn, PyTorch, PyMC, ArviZ.

---

## 📜 License
This project is open-source and licensed under MIT – feel free to use it.
