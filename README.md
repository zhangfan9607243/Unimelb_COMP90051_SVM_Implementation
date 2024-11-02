# Unimelb Comp90051 SVM Implementation

## Project Introduction

This repository contains the code and results for implementing and experimenting with several **Support Vector Machine (SVM)** algorithms. 

### Part 1: Primal SVM with Stochastic Gradient Descent (SGD)
- **Objective:** Implement a soft-margin SVM using the primal formulation and SGD for training.
- **Implementation:** `PrimalSVM` class with `fit`, `predict`, and `__init__` methods.
- **Experiment:** Tune hyperparameters and visualize decision boundaries.

### Part 2: Dual SVM Formulation
- **Objective:** Implement the dual formulation of soft-margin SVM with a linear kernel.
- **Implementation:** `DualSVM` class with training via SGD and support for kernelized versions.
- **Experiment:** Compare weights with primal SVM and identify support vectors.

### Part 3: Kernel Implementation
- **Objective:** Use polynomial and RBF kernels along with the linear kernel to classify data.
- **Implementation:** Implement and compare different kernels.
- **Experiment:** Analyze decision boundaries and select the most appropriate kernel for the dataset.

### Part 4: Sequential Minimal Optimization (SMO)
- **Objective:** Implement the SMO algorithm for SVMs with different kernels.
- **Experiment:** Train the SMO-based SVM on the **fashion MNIST** dataset and compare results using different heuristic selection functions.

## Files Structure

- **`SVM Implementation.ipynb`**: Contains the full implementation of the SVM algorithms, including all four tasks mentioned above.
- **`train.csv`**: Training dataset.
