# 🧠 Machine Learning Foundations (From Scratch)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

A comprehensive collection of core machine learning algorithms implemented **entirely from scratch** in Python. 

Rather than relying on high-level ML libraries, this repository focuses on the raw mathematical implementation of predictive analysis, data clustering, and dimensionality reduction. This project was developed to demonstrate a deep, under-the-hood understanding of how machine learning models truly work.

## 🧮 Implemented Models & Use Cases

### 1. Neural Networks (`Neural Network.ipynb`)
* **Concept:** Artificial Neural Network (ANN) implementation.
* **Use Case:** Handwriting recognition. The model was trained and evaluated on the famous **MNIST dataset** to accurately classify handwritten digits.
* **Key Mechanisms:** Forward propagation, backpropagation, activation functions, and weight updates using gradient descent.

### 2. Logistic Regression (`Logistic_Regression.ipynb`)
* **Concept:** A fundamental classification algorithm.
* **Use Case:** Predicting university admission chances. The model classifies an applicant's probability of admission based on historical exam scores.
* **Key Mechanisms:** Probability calculation using the sigmoid function, cost function optimization, and decision boundaries mapping.

### 3. K-Means & PCA (`K-Means and PCA.ipynb`)
* **Concept:** Unsupervised learning for clustering and dimensionality reduction.
* **Use Case:** Discovering patterns in 2D spatial data (tested on both Convex and Non-Convex 'Moons' datasets).
* **Key Mechanisms:** * **K-Means:** Iterative centroid assignment and variance minimization.
  * **PCA (Principal Component Analysis):** Covariance matrix calculation, eigenvalues/eigenvectors extraction, and data projection.

## 🛠️ Tech Stack & Tools
* **Language:** Python 3
* **Environment:** Jupyter Notebooks (for interactive data visualization and step-by-step algorithm execution)
* **Libraries:** NumPy (for linear algebra and matrix operations), Pandas (for data manipulation), Matplotlib (for plotting and decision boundary visualization).

## 🚀 How to Explore
To view the code and the mathematical breakdown:
1. Simply click on any of the `.ipynb` files above. GitHub will render the Jupyter Notebook natively in your browser.
2. Scroll through to see the custom algorithm implementations, mathematical formulas, and the final plotted results.
