# Tensor Contraction Validation Notebook (SymPy + Colab)

This repository contains a reproducible symbolic validation notebook that critically analyzes tensor index usage in the paper:

**Lindgren, J. et al. (2025). "Electromagnetism as a purely geometric theory." Journal of Physics: Conference Series, 2987(1), 012001.**  
[DOI: 10.1088/1742-6596/2987/1/012001](https://doi.org/10.1088/1742-6596/2987/1/012001)

## 📘 Purpose

This notebook independently tests the mathematical consistency of the tensor expressions in Lindgren et al. (2025), as critiqued by Dr. Sabine Hossenfelder and further analyzed in the peer-reviewed response:

> *Valamontes, A. (2025). "Scientific Commentary and Symbolic Validation of Lindgren (2025): Index Logic, Gauge Invariance, and Electrodynamic Coherence." Demokritos Scientific Journal: Foundation of Open Physics, Vol. 1, Issue 1.*

## 🔬 What It Does

- Uses `sympy.tensor.tensor` to construct symbolic tensors
- Validates Einstein summation convention
- Detects repeated dummy indices and invalid contractions
- Reproduces failure cases from Lindgren (2025) equations (esp. Eq. 25 and 36)
- Confirms critiques from Hossenfelder's public review [YouTube Link](https://www.youtube.com/watch?v=ll2hrh_BJfQ)

## 📂 Files

- `tensor_validation.ipynb` — Main Jupyter notebook for symbolic tensor analysis
- `screenshots/` — Output screenshots validating specific index errors
- `references.bib` — BibTeX file with all relevant citations
- `README.md` — This file

## 📖 How to Run

You can run this notebook on [Google Colab](https://colab.research.google.com) without installing anything locally.

Click to open: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/tensor-validation-lindgren/blob/main/tensor_validation.ipynb)

## 📑 Citation

Once this repository is archived via Zenodo, please cite as:

