# Tumor Feature Segmentation Using K-Means and PCA

## Project Overview

This project explores patterns in breast tumor characteristics using unsupervised machine learning techniques.

The primary objective is to identify groups of tumors with similar characteristics through K-Means clustering and visualize underlying patterns using Principal Component Analysis (PCA).

Unlike supervised classification, this project focuses on discovering patterns without using diagnostic labels to train the clustering model.

## Dataset

**Dataset:** Breast Cancer Wisconsin Diagnostic Dataset

**Source:** UCI Machine Learning Repository

- **Observations:** 569
- **Features:** 30 numerical variables
- **Diagnostic categories:** Benign and Malignant

The dataset includes measurements of cell nuclei, such as radius, texture, perimeter, area, smoothness, compactness, concavity, and symmetry.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Exploration and Preparation

- Examined the dataset structure.
- Checked for missing values.
- Selected numerical features for clustering.
- Standardized features using StandardScaler.

### 2. K-Means Clustering

- Applied K-Means clustering to identify groups of tumors with similar characteristics.
- Explored cluster assignments and feature patterns.
- Examined differences between the identified
