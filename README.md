# Bias–Variance in Unsupervised Learning

This project explores the bias–variance trade-off in unsupervised learning using clustering and mixture models in Python.

## Overview

The notebook studies how model complexity affects performance in unsupervised learning, with a focus on:

- K-means clustering
- Gaussian Mixture Models (GMM)
- stability across random initializations
- train and validation log-likelihood
- empirical bias–variance estimation across multiple datasets

A synthetic 2D Gaussian mixture is used as the ground-truth data-generating process, which makes it possible to compare clustering results with known underlying components.

## Objectives

- Analyze clustering behavior under different model complexities
- Compare K-means and GMM on synthetic data
- Study stability and quality across multiple runs
- Explore empirical bias–variance in an unsupervised setting

## Methods

The notebook includes four main parts:

1. Synthetic data generation from a 2D Gaussian mixture  
2. K-means experiments for different values of K  
3. GMM experiments for different values of K and covariance types  
4. Empirical bias–variance estimation over multiple sampled datasets  

## Models Used

- K-means
- Gaussian Mixture Models (GMM)

## Evaluation Tools

- Distortion (inertia)
- Stability via Adjusted Rand Index (ARI)
- ARI with respect to ground truth
- Train and validation log-likelihood
- Validation negative log-likelihood across repeated datasets

## Tools and Libraries

- Python
- NumPy
- Matplotlib
- scikit-learn

## Repository Contents

- `bias_variance_unsupervised_learning.ipynb` — main notebook with experiments, plots, and analysis

## Author

Said Abolhassan Razavi  
Master’s student in Artificial Intelligence at Université Paris-Saclay
