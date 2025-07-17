# Features-Transformation-Lab

A hands‑on Jupyter Notebook exploring **why** and **how** to transform features for machine learning and deep learning pipelines.
- **Standardization(Why standardization?):** 
Standardization comes into picture when features of input data set have large differences between their ranges, or simply when they are measured in different measurement units (e.g., Pounds, Meters, Miles … etc).

## 🚀 Why Transform Features?
Machine learning algorithms often assume that all features operate on a comparable scale:
- **Linear Regression & Gradient Descent:**  
  Large‑scale features can dominate the loss landscape, making it harder to find the global minima efficiently.
- **Distance‑Based Methods (KNN, K‑Means, Hierarchical Clustering):**  
  Euclidean distance is sensitive to scale; unbalanced features skew nearest neighbors and cluster centroids.
- **Deep Learning (ANN, CNN, RNN):**  
  Activation gradients explode or vanish when inputs have wildly different ranges. Standardization helps gradients flow smoothly.


We try to bring all the variables or features to a similar scale. standarisation means centering the variable at zero. z=(x-x_mean)/std

  ## 🎯 Types Of Transformation
1. Normalization And Standardization
2. Scaling to Minimum And Maximum values
3. Scaling To Median And Quantiles
4. Guassian Transformation
5. Logarithmic Transformation
6. Reciprocal Trnasformation
7. Square Root Transformation
8. Exponential Trnasformation
9. Box Cox Transformation

