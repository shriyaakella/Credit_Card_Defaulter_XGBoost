# Credit_Card_Defaulter_XGBoost
This repository contains an example of the `XGBoost` algorithm. The goal is to use a Jupyter notebook and data from the [UCI repository:
default of credit card clients Data Set](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients#) to predict whether a person will deafult credit card payment in Taiwan.

We use XGBoost (Extreme Gradient Boost) algorithm for classification as it can handle skewed data well.

The steps involved in this notebook are as follows:
* Exploratory Data Analysis
* Data preprocessing
* One Hot Encoding to help format the data in a way that scikit-learn can process it
* Naive XGBoost for the first run of classification
  * Cross Validation in order to tune the hyperparameters
  * Plotting confusion matrices to compare the results
* Building the tree and visualising it

#### Notebooks
[Credit_Card_Defaulter_XGBoost.ipynb](https://github.com/shriyaakella/Credit_Card_Defaulter_XGBoost)

#### Technologies
* [Python](https://www.python.org/)
* [XGBoost](https://github.com/dmlc/xgboost)
* [Scikit Learn](https://scikit-learn.org/stable/)
* [Pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)
* [Graphviz](https://graphviz.org/)

### Visualising the tree
![xgb](https://user-images.githubusercontent.com/84118083/118371731-8f2cd280-b5cb-11eb-9a60-0ffe168e2821.png)

