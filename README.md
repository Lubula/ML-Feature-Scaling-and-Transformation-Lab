# ML-Feature-Scaling-and-Transformation-Lab
A hands-on Jupyter Notebook collection exploring why and how to transform features for machine learning and deep learning pipelines.
This repo demonstrates the impact of scaling, normalization, and Gaussian transformations on model performance.

## 🚀 Why Transform Features?
Many machine learning algorithms assume features operate on similar scales:
- Linear Regression & Gradient Descent
Large-scale features can dominate the loss function, slowing or misdirecting optimization.
- Distance-Based Models (KNN, K-Means)
Uneven feature scales distort Euclidean distance, affecting clustering and neighbor searches.
- Deep Learning Models (ANN, CNN, RNN)
Extreme feature values can cause vanishing or exploding gradients.
Feature transformation ensures fair contribution of all variables by bringing them to a similar scale.

## 🎯 Types Of Transformation
1. [Normalization And Standardization](https://github.com/Lubula/ML-Feature-Scaling-and-Transformation-Lab/blob/main/01-normalization-standardization.ipynb)
2. [Scaling to Minimum And Maximum values | Scaling To Median And Quantiles](https://github.com/Lubula/ML-Feature-Scaling-and-Transformation-Lab/blob/main/02-scaling-min-max-median-quantiles.ipynb)
3. [Guassian Transformations:](https://github.com/Lubula/ML-Feature-Scaling-and-Transformation-Lab/blob/main/03-gaussian-transformations.ipynb)
   - Logarithmic Transformation
   - Reciprocal Transformation
   - Square Root Transformation
   - Exponential Transformation
   - BoxCOx Transformation (will explain in detail)

📚 Contents
Each notebook focuses on a specific transformation technique:
- Normalization & Standardization
- Centers features around zero mean and unit variance.
- Ideal for algorithms assuming Gaussian distributions.
- Scaling to Min–Max & Median–QuantileMin–Max scaling: maps values to [0, 1].
- Median–Quantile scaling: robust to outliers.
- Gaussian Transformations
- Logarithmic, Reciprocal, Square Root, Exponential, Box-Cox (Helps meet normality assumptions.)
