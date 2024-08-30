# Advanced Regression and Clustering with Kernel Methods

## Overview

This project explores advanced regression and clustering techniques using kernel methods. By applying kernel functions, the project demonstrates how data can be transformed into higher-dimensional spaces for enhanced regression and clustering performance. Key techniques include kernel ridge regression, landmark-based ridge regression, kernel K-means clustering, and handcrafted feature K-means clustering.

## Techniques Used

- **Kernel Ridge Regression**: Utilizes kernel functions to perform ridge regression in high-dimensional spaces, improving flexibility for nonlinear data.
- **Landmark-Based Ridge Regression**: Employs landmark points to compute kernel features for ridge regression, optimizing for accuracy and efficiency.
- **Kernel K-Means Clustering**: Applies kernel methods to K-means clustering, handling non-linearly separable data.
- **Handcrafted Feature K-Means**: Enhances K-means clustering by transforming data into handcrafted feature spaces.

## Implementation

1. **Kernel Ridge Regression**: Run `Kernel_ridge.py` to perform regression with RBF kernels, adjusting lambda values to optimize RMSE.
2. **Landmark-Based Ridge Regression**: Use `Landmark_ridge.py` to apply ridge regression with kernel features from randomly selected landmarks, exploring accuracy versus computational cost.
3. **Kernel K-Means Clustering**: Execute `Kernel_Kmeans.py` to cluster data using kernelized K-means, evaluating clustering effectiveness through visualizations.
4. **Handcrafted Feature K-Means**: Run `Handcrafted_Means.py` to apply K-means on data transformed through feature engineering, comparing results in original and transformed spaces.

## Setup

- **Python 3.x**
- **NumPy**
- **Matplotlib**
- **Pandas**
- **Scikit-learn**

## Dataset

Available in the `data/` folder:
- `ridgetrain.txt`: Training data for regression.
- `ridgetest.txt`: Testing data for regression.
- `kmeans_data.txt`: Data for clustering.

## Results

The project showcased the power of kernel methods in regression and clustering. Kernel ridge regression achieved lower RMSE with various lambda settings, and kernel K-means clustering provided superior results on complex datasets compared to standard K-means.

## Acknowledgments

This work was conducted for the CS771 course, focusing on kernel methods in machine learning. Thanks to the course instructors and dataset providers for their support.

**Note**: Please acknowledge this project if you use any code or insights from it.
