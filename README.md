# Unimelb Comp90051 SVM Implementation

## Project Introduction

This repository contains the code and results for implementing and experimenting with several **Support Vector Machine (SVM)** algorithms. 

### Part 1: Primal SVM with Stochastic Gradient Descent (SGD)
- Implement a soft-margin SVM using the primal formulation and SGD for training.
- Implement `PrimalSVM` class with `fit`, `predict`, and `__init__` methods.
- Tune hyperparameters and visualize decision boundaries.

### Part 2: Dual SVM Formulation
- Implement the dual formulation of soft-margin SVM with a linear kernel.
- Implement `DualSVM` class with training via SGD and support for kernelized versions.
- Compare weights with primal SVM and identify support vectors.

### Part 3: Kernel Implementation
- Use polynomial and RBF kernels along with the linear kernel to classify data.
- Implement and compare different kernels.
- Analyze decision boundaries and select the most appropriate kernel for the dataset.

### Part 4: Sequential Minimal Optimization (SMO)
- Implement the SMO algorithm for SVMs with different kernels.
- Train the SMO-based SVM on the **fashion MNIST** dataset and compare results using different heuristic selection functions.
- Define a customized heuristic function.

## Files Structure

- **`SVM Implementation.ipynb`**: Contains the full implementation of the SVM algorithms, including all four tasks mentioned above.
- **`train.csv`**: Training dataset.
