# Machine-Learning-Projects

Welcome to my Machine Learning Projects repository! This collection features machine learning algorithms implemented from scratch and predictive analytics techniques applied to real-world datasets. Each notebook includes code, explanations, and results from different machine learning techniques.

## Repository Structure
This repository is organized into two main folders:\
📁 ML_from_scratch/ \
📁 unsupervised_learning/

1️⃣ ML_from_scratch/ \
This folder contains implementations of key machine learning algorithms without the use of high-level libraries like Scikit-Learn.
- **Clustering with K-Means, K-Modes, and K-Prototypes**\
This notebook covers clustering algorithms, starting with k-means and extending to k-modes and k-prototypes. The focus is on understanding how clustering works with numerical and categorical data, and the differences in their behavior depending on the type of data being processed.

- **KNN and Logistic Regression**\
This notebook demonstrates the implementation of K-Nearest Neighbors (KNN) for classification and Logistic Regression. The goal was to build these models from scratch to understand how the algorithms classify data. It also covers key concepts such as distance metrics used in KNN, as well as the sigmoid function, cost function, and gradient descent in Logistic Regression.

- **Decision Tree**\
This notebook explores decision trees, including both the process of building the tree and techniques for pruning to prevent overfitting. The implementation covers the algorithm's ability to recursively partition data based on features and the decision rules created at each node.

2️⃣ unsupervised_learning/ \
This folder applies unsupervised learning techniques to real-world datasets, focusing on dimensionality reduction, clustering, and customer segmentation.
- PCA + Clustering (Customer Segmentation)
  - Dataset: Nightclub customer survey
  - Techniques: Principal Component Analysis (PCA) for dimensionality reduction + K-Means & Hierarchical Clustering for segmentation.
  - Insights: Identified distinct customer segments to help optimize pricing strategies.

## How to Use
1. Clone the repository to your local machine or open the individual Google Colab notebooks for execution:
```bash
git clone https://github.com/matija13795/Machine-Learning-Projects
```
2. Each file contains a Jupyter Notebook with explanations and code. Follow the markdown cells for a detailed breakdown of the concepts and implementation.

## Requirements
To run the code, make sure you have the following libraries installed:
- NumPy
- Pandas
- Matplotlib
- Seaborn
