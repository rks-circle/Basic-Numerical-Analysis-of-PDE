# Basic Numerical Analysis of PDEs

This repository contains basic numerical implementations for solving **partial differential equations (PDEs)** using standard numerical methods. The main goal is to provide simple, transparent examples for understanding how PDEs can be discretized and solved computationally.

## Methods Covered

* **Finite Difference Method (FDM)**

  * Five-point stencil
  * Nine-point stencil
* **Finite Element Method (FEM)**

The repository includes both **Jupyter notebooks** containing the implementations and **PDF documents** presenting the corresponding calculations and results.

## Repository Contents

* `FD_five_pt_stencil.ipynb` — Implementation of the five-point finite-difference stencil.
* `FD_nine_pt_stencil.ipynb` — Implementation of the nine-point finite-difference stencil.
* `FEM_implementation.ipynb` — Basic implementation of the finite-element method.
* Corresponding `.pdf` files provide the associated notes/results.

## Purpose

This repository is intended as a learning and reference resource for developing a basic understanding of numerical PDE techniques, particularly the transition from the continuous differential equations to their discrete computational form.

The methods presented here provide a foundation for more advanced numerical techniques used in computational physics, engineering, and scientific computing.

## Requirements

The notebooks are written in **Python** and can be run using Jupyter Notebook or JupyterLab.

Typical dependencies include:

```bash
numpy
scipy
matplotlib
```

Additional packages may be required depending on the FEM implementation.

## Author

**Rishabh Kumar Singh**

[GitHub Repository](https://github.com/rks-circle/Basic-Numerical-Analysis-of-PDE)
