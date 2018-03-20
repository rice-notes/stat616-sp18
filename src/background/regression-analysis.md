# Regression Analysis

A set of statistical processes for estimating relationships among variables.
In particular, regression analysis is used when the focus is on the
relationship between a dependent variable (response) and one or more indpendent
variables (predictors).  These relationships are formalized by the following
equation:

$$
E(Y | X) = f(X, \beta)
$$

where  
* $$Y$$ is a the dependent variable
* $$X$$ is a independent variables
* $$\beta$$ represents the unknown parameters


### Example: Standard Multiple Linear Regression

This regression model is a linear model relating $$p$$ predictors with a single
response variable:

$$
Y = X\beta + \epsilon
$$

where $$Y, \epsilon \in \mathbb{R}^{n \times 1}$$, $$X \in \mathbb{R}^{n \times
p + 1}$$, $$\beta \in \mathbb{R}^{p + 1 \times 1}$$, and each $$\epsilon_i \sim
N(0, \sigma^2)$$. $\epsilon$ represents the random error in our observations.

Note that we assume that our error is i.i.d normal, or that:
* the errors are normal ($$\epsilon_i \sim N(0, \sigma^2)$$)
* the errors are independent
* the errors are are homoescadastic and have variance $$\sigma^2$$
