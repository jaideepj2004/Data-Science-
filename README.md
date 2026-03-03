# Data Science — PW Skills Course Notebooks

A comprehensive collection of **Jupyter Notebooks** from the **PW Skills Data Science course**, covering the full data science curriculum from Python fundamentals through advanced machine learning. Contains 60+ daily assignment notebooks spanning January–April.

---

## Table of Contents

- [Overview](#overview)
- [Topics Covered](#topics-covered)
- [Notebook Highlights](#notebook-highlights)
- [Tech Stack](#tech-stack)
- [Repository Structure](#repository-structure)
- [Setup & Running](#setup--running)

---

## Overview

All notebooks in this repository represent coursework and daily assignments from the PW Skills Data Science curriculum. Notebooks are named by date (e.g., `02 feb assignment.ipynb`, `10th_march.ipynb`). Two special internal assignments use saved models and structured ML pipelines.

---

## Topics Covered

| Module | Topics |
|---|---|
| Python Fundamentals | Variables, data types, control flow, functions, OOP |
| Data Manipulation | Pandas (DataFrames, merging, groupby, reshaping) |
| Numerical Computing | NumPy arrays, vectorized operations |
| Visualization | Matplotlib, Seaborn (829KB notebook), Plotly (117KB notebook) |
| Statistics | Descriptive stats, distributions, hypothesis testing |
| Machine Learning | Naive Bayes, SVM with hyperparameter tuning, Random Forest |
| ML Pipelines | scikit-learn Pipelines with preprocessing and modeling |
| Model Persistence | `tuned_svc_model.pkl` (saved and reloaded SVC) |

---

## Notebook Highlights

| Notebook | Description |
|---|---|
| `seaborn.ipynb` (829KB) | Comprehensive Seaborn visualization reference |
| `plotly.ipynb` (117KB) | Interactive Plotly charts |
| `naive_bayes_internal_assignment.ipynb` | Internal assignment: Naive Bayes classifier |
| `internal_assignment_randomForst_pipeline.ipynb` | Internal: Random Forest with scikit-learn Pipeline |
| `1st_april.ipynb` (141KB) | Large April assignment |
| `24th_march.ipynb` (301KB) | Large March assignment |
| `02 feb assignment.ipynb` | Start of February assignments |

**Dataset:** `student_data.csv` — used across multiple notebooks
**Saved model:** `tuned_svc_model.pkl` — SVC after hyperparameter tuning

---

## Tech Stack

| Component | Technology |
|---|---|
| Notebooks | Jupyter (.ipynb) |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Plotly |
| Machine Learning | scikit-learn (Naive Bayes, SVM, Random Forest, Pipelines) |
| Model Persistence | joblib / pickle (`.pkl`) |

---

## Repository Structure

```
Data-Science-/
├── 02 feb assignment.ipynb    # Daily assignments — February
├── 05 Feb assignment.ipynb    # ...
├── ...                        # 60+ date-named notebooks (Jan–April)
├── seaborn.ipynb              # Seaborn reference (829KB)
├── plotly.ipynb               # Plotly interactive (117KB)
├── naive_bayes_internal_assignment.ipynb
├── internal_assignment_randomForst_pipeline.ipynb
├── student_data.csv           # Dataset used in assignments
├── tuned_svc_model.pkl        # Saved hyperparameter-tuned SVC
└── README.md
```

---

## Setup & Running

```bash
git clone https://github.com/jaideepj2004/Data-Science-.git
cd "Data-Science-"
pip install pandas numpy scikit-learn matplotlib seaborn plotly jupyter
jupyter notebook
```

Open any notebook from the Jupyter interface. Notebooks are self-contained and run top-to-bottom.
