# Logistic Regression On Breast Cancer Data Set
In this program, we plot the logistic function and perform logistic regression on a breast cancer data set to detect if the cells are benign or malignant.
This data set is described here:

https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin

Each sample is a collection of features that were manually recorded by a physician upon inspecting a sample of cells from fine needle aspiration.

We could use the sklearn built-in LogisticRegression class to find the weights for the logistic regression problem. The fit routine in that class has an optimizer to select the weights to best match the data. To understand how that optimizer works, in this problem, we will build a very simple gradient descent optimizer from scratch.
