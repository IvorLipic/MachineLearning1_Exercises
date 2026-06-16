# Machine Learning 1 - Laboratory Exercises

Repository of laboratory exercises for the course **"Strojno učenje 1"** (Machine Learning 1) at the University of Zagreb, Faculty of Electrical Engineering and Computing (FER), academic year 2024/2025.

## Repository Structure

- `lab1/` – **Linear Regression**
  - Polynomial regression (`PolynomialFeatures` + `LinearRegression`)
  - Normal equation and pseudoinverse
  - Model selection, bias-variance tradeoff
  - Ridge regression (L2 regularization)

- `lab2/` – **Linear Discriminative Models & Logistic Regression**
  - Linear regression as a classifier (`RidgeClassifier`)
  - Multi-class classification (one-vs-rest)
  - Logistic regression: sigmoid function, cross-entropy loss
  - Custom batch and stochastic gradient descent implementation

- `lab3/` – **Support Vector Machines & Nonparametric Methods**
  - SVM with linear, polynomial, and RBF kernels
  - Hinge loss
  - Grid search hyperparameter optimization (C, gamma)
  - Feature scaling (`MinMaxScaler`)
  - k-Nearest Neighbors classifier
  - K-means clustering, elbow method, silhouette analysis

- `lab4/` – **Parameter Estimation, Probabilistic Graphical Models, Clustering**
  - ML estimation (Bernoulli, Gaussian)
  - MAP estimation with Beta priors
  - Covariance matrix (biased vs unbiased estimators)
  - Bayesian Networks with `pgmpy` (sprinkler example, exact inference via Variable Elimination)
  - Explaining away phenomenon
  - K-means clustering and silhouette analysis

## Prerequisites

- Python 3.7+
- `numpy`, `scipy`, `matplotlib`
- `scikit-learn`
- `pgmpy` (for lab 4)

## Acknowledgements

University of Zagreb, Faculty of Electrical Engineering and Computing (FER)

Original notebook templates by **Jan Šnajder** and **Domagoj Alagić** (c) 2015–2025.

Course: [Strojno učenje 1](http://www.fer.unizg.hr/predmet/struce1)
