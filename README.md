Project Overview

This project demonstrates Principal Component Analysis (PCA) on the Breast Cancer Wisconsin dataset available in Scikit-learn.

PCA is an unsupervised dimensionality reduction technique that transforms high-dimensional data into a smaller set of principal components while preserving as much variance as possible.

The project includes:

Data preprocessing
Feature scaling
PCA implementation
Explained variance analysis
Correlation heatmap
2D visualization using principal components
Dataset

Source:

from sklearn.datasets import load_breast_cancer

Dataset contains

569 samples
30 numerical features
Binary classification

Classes

Malignant
Benign
Workflow
Load Dataset
Explore Dataset
Standardize Features
Apply PCA
Visualize Principal Components
Analyze Explained Variance
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Results
Reduced 30 features into 2 principal components for visualization.
First two principal components retained approximately 63% of the total variance.
Approximately 10 principal components retained 95% of the dataset information.
Future Improvements
Apply PCA before classification algorithms such as Logistic Regression, SVM, KNN, or Random Forest.
Compare model performance before and after dimensionality reduction.
Extend the analysis to other high-dimensional datasets.
