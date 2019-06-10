# Machine Learning

[![License](http://img.shields.io/:license-mit-blue.svg)](LICENSE)

## Description
Welcome to our __Machine Learning__ reposetory! Here you will find various projects from __polynomial regression__ to fully-connected __neural networks__ from scratch, __SVM__ and __Gaussian Processes__!

### __Lab 1__: Linear Regression and Overfitting

#### Part 1: Polynomial Regression

<p align="center">
  <img src="readme_imgs/polynomial_regression.png" width="800" />
</p>
<p align="center">
    Polynomial regressions as prediction function, along with the data and the original sine function of various polynomial order. 
</p>



<p align="center">
  <img src="readme_imgs/regularized_linear_regression.png" width="400" />
  <img src="readme_imgs/best_cross-validated_fit.png" width="400" />
</p>

<p align="center">
    <b>Left:</b> Polynomial regression with and without regularization. In regularized polynomial regression, the regularization term acts as a penalty term and has the desired effect of reducing the magnitude of the coefficients.
    <b>Right:</b> Best cross-validated fit (M =  5, lambda = 1.0)
</p>

#### Part 2: Bayesian Linear (Polynomial) Regression
<p align="center">
  <img src="readme_imgs/baysian_regression_2.png" width="400" />
  <img src="readme_imgs/baysian_regression_1.png" width="400" />
</p>

<p align="center">
    Bayesian linear regression model
    <b>Left:</b> Plot of predictive distribution
    <b>Right:</b> 100 polynomials sampled from the parameter posterior distribution
</p>

### __Lab 2__: Classification

#### Part 1: Multiclass logistic regression

<p align="center">
  <img src="readme_imgs/mnist.png" width="300" />
  <img src="readme_imgs/visualization_of_weights.png" width="450" />
</p>
<p align="center">
    MNIST:
    <b>Left:</b>  visualisation of the first 8 digits of the trainingset
    <b>Right:</b> visualization of leanred weights.
</p>

<p align="center">
  <img src="readme_imgs/easiest_digits.png" width="300" />
  <img src="readme_imgs/hardest_digits.png" width="300" />
</p>
<p align="center">
    <b>Left:</b>  Easiest digits for classification.
    <b>Right:</b> Hardest digits for classification
</p>




#### Part 2: Multilayer perceptron

<p align="center">
  <img src="readme_imgs/weights_0.png" width="250" />
  <img src="readme_imgs/weights_4.png" width="250" />
  <img src="readme_imgs/weights_9.png" width="250" />
</p>
<p align="center">
    Weights of the hidden layer at epoch 0, 4 and 9.
</p>

<p align="center">
  <img src="readme_imgs/activation_functions.png" width="800" />
</p>
<p align="center">
    Different activation functions.
</p>


#### Comparison

<p align="center">
  <img src="readme_imgs/logistic_plot.png" width="300" />
  <img src="readme_imgs/mpl_plot.png" width="370" />
</p>
<p align="center">
    <b>Left:</b>  Multiclass logistic regression
    <b>Right:</b> Multilayer perceptron
</p>



### __Lab 3__: Gaussian Processes and Support Vector Machines


#### Part 1: Gaussian Processes

<p align="center">
  <img src="readme_imgs/gp.png" width="700" />
</p>
<p align="center">
    Gaussian Processes.
</p>

#### Part 2: Support Vector Machines

<p align="center">
  <img src="readme_imgs/svm.png" width="700" />
</p>
<p align="center">
    Support Vector Machines.
</p>


###### _Acknowledgement - References_

_The majority of the projects come from the lab assignments of the [Machine Learning 1](http://coursecatalogue.uva.nl/xmlpages/page/2018-2019-en/search-course/course/63074) course of the MSc in Artificial Intelligence at the University of Amsterdam._