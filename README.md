# Introduction
This is an implementation of polynomial regression using both Batch Gradient Descent and Stochastic Gradient Descent.

# Overview
In this notebook, I generate a synthetic dataset using NumPy and visualize it using Matplotlib. Then, I fit a polynomial regression model to the dataset using both Batch Gradient Descent and Stochastic Gradient Descent. I compare the performance of both methods by plotting the learned model and the original dataset.

# Dependencies
<ul>
<li>numpy</li>
<li>matplotlib</li>
</ul>

# Dataset
We generate a synthetic dataset of 100 points using NumPy. The input features X are sampled uniformly from the range `[-3, 3]`. The output targets `y` are generated using the function `y = 0.5*X^2 + X + 2 + noise`, where `noise` is a Gaussian noise term.
<img src="https://github.com/SanthoshV14/polynomial-regressor-with-batch-and-stochastic-gradientdescent/blob/main/img/dataset.png" />

# Models
Polynomial regression model of degree 2 to the dataset using both Batch Gradient Descent and Stochastic Gradient Descent.
<ol>
<li>Batch Gradient Descent</li>
We implement the Batch Gradient Descent algorithm by computing the gradient of the cost function with respect to the model parameters using the entire training set. We update the model parameters by taking a step in the direction of the negative gradient, multiplied by a learning rate hyperparameter.

<li>Stochastic Gradient Descent</li>
We implement the Stochastic Gradient Descent algorithm by computing the gradient of the cost function with respect to the model parameters using a randomly selected single instance from the training set. We update the model parameters by taking a step in the direction of the negative gradient, multiplied by a learning rate hyperparameter.
</ol>

# Results
We visualize the original dataset and the learned models obtained by both Batch Gradient Descent and Stochastic Gradient Descent. The plots show that both methods learn similar models that fit the dataset well.
<ol>
<li>Batch Gradient Descent</li>
<img src="https://github.com/SanthoshV14/polynomial-regressor-with-batch-and-stochastic-gradientdescent/blob/main/img/batch-prediction-plot.png" />

<li>Stochastic Gradient Descent</li>
<img src="https://github.com/SanthoshV14/polynomial-regressor-with-batch-and-stochastic-gradientdescent/blob/main/img/stochastic-prediction-plot.png" />
</ol>

# Author
Santhos Vadivel </br>
Email - ssansh3@gmail.com </br>
LinkedIn - https://www.linkedin.com/in/santhosh-vadivel-2141b8126/ </br>
