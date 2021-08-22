# Machine Learning Optimization

This repository includes four different Python notebooks that perform various tasks aimed at achieving
more efficieny in machine learning including implementing and comparing various loss functions
and/or gradient descent methods and depicting the importance of numerical correctness in algorithms.

This is done in order to better understand how machine learning can be optimized and to learn more about
various loss and gradient descent methods.

The details for each of the four notebooks are mentioned below:


**Gradient Descent vs. Proximal Gradient Descent**
This notebook contains the implementation and comparison of regular gradient descent with proximal gradient
descent over 250 iterations. The loss used for the comparison is L1 regularized logistic loss.


**Gradient Descent Variations**
This notebook contains the implementation of five variations of gradient descent and the results of
comparing all of these variations with each other after 250 iterations. These implementations are
tested with two different loss functions: logistic loss and hinge loss. The results are shown graphically.

The five gradient descent variations implemented and compared are:
* Gradient Descent with Fixed Learning Rate
* Gradient Descent with Armijo Line Search
* Accelerated Gradient Descent
* Conjugate Gradient (Fletcher-Reeves)
* Barzelia-Borwein Step Gradient Descent (Approach 1)


**Loss Functions**
This notebook contains the implementation of several loss functions in Python. The functions are written
inefficiently via a for loop for understanding and vectorized for actual use. The two versions are then
verified to be equivalent and compared in running time. Finally, the numerical and calculated gradients
are compared.

The four loss functions are:
* Logistic Loss
* Hinge Loss/SVMs
* Simple Two Layer Function
* Least Squares Loss


**Numerical Correctness**
This notebook shows how numpy methods for mathematics can often lead to misleading or incorrect results.
It also explains how these functions can be changed such that they can become numerically correct functions.

The three functions are:
* log(1 + exp(-x))
* log(exp(x1) + exp(x2))
* exp(x1) / (exp(x1) + exp(x2))


2020