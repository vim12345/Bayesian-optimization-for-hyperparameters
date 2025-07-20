# Bayesian-optimization-for-hyperparameters

# Description:
Bayesian Optimization is a smart hyperparameter tuning technique that builds a probabilistic model of the objective function and chooses the next set of hyperparameters to evaluate based on expected improvement. Unlike grid search, it’s much more efficient and sample-aware. In this project, we’ll use skopt (Scikit-Optimize) to tune an SVM classifier on the Iris dataset.

# 💡 What Makes Bayesian Optimization Powerful:
* Selects next trial using probabilistic models (like Gaussian Processes)

* Finds optimal parameters using fewer evaluations

* Efficient for expensive models or large search spaces
