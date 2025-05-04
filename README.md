# Tensor Index Validation Notebook (SymPy + Colab)

This repository provides a symbolic tensor validation notebook that critically examines the mathematical consistency of index operations used in:

**Lindgren, J. et al. (2025). "Electromagnetism as a purely geometric theory." Journal of Physics: Conference Series, 2987(1), 012001.**  
[DOI: 10.1088/1742-6596/2987/1/012001](https://doi.org/10.1088/1742-6596/2987/1/012001)

---

## 🎯 Purpose

This notebook performs reproducible symbolic tests of tensor operations used in the Weyl-based formulation proposed by Lindgren et al. (2025), as independently reviewed by Dr. Sabine Hossenfelder and formally analyzed in:

> *Valamontes, A. (2025). “Scientific Commentary and Symbolic Validation of Lindgren (2025).”*  
> *Demokritos Scientific Journal: Foundation of Open Physics, Vol. 1, Issue 1.*

---

## 🔬 What It Does

- Constructs symbolic tensor expressions using `sympy.tensor.tensor`
- Validates Einstein summation convention and index uniqueness
- Flags repeated dummy indices and invalid free-bound contractions
- Tests vector division and null geodesic logic
- Reproduces failure cases from Equations 25 and 36 in the Lindgren paper

---

## 📂 Repository Contents

- `tensor_validation.ipynb` — Main Colab-ready Jupyter notebook
- `screenshots/` — Output screenshots for reproducibility
- `references.bib` — BibTeX entries for all cited sources
- `.CITATION.cff` — Citation metadata for Zenodo and GitHub
- `README.md` — This file

---

## 🚀 Run the Notebook

You can open and run the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Galactic-Code-Developers/Tensor-Index-Validation-Lindgren2025/blob/main/tensor_validation.ipynb)

---

## 📘 Citation

If you use this repository in academic or scientific work, please cite:

**Valamontes, A. (2025).**  
*Tensor Index Validation Notebook (SymPy + Colab).*  
Zenodo. [https://doi.org/10.5281/zenodo.15335886](https://doi.org/10.5281/zenodo.15335886)

```bibtex
@software{valamontes_tensor_validation_2025,
  author       = {Valamontes, A.},
  title        = {Tensor Index Validation Notebook (SymPy + Colab)},
  year         = 2025,
  publisher    = {Kapodistian Academy of Science},
  doi          = {10.5281/zenodo.15335886},
  url          = {https://github.com/Galactic-Code-Developers/Tensor-Index-Validation-Lindgren2025}
}
