HW2
================

### Q1. lm vs stan\_glm (4 points)

Describe the differences between using `lm()` or `stan_glm()`. Make sure
to cover:

-   pros and cons of both approaches
-   differences in assumptions
-   differences in intepreting model output

### Q2. Washington, D.C. housing

Using the Washington, DC dataset create a linear model to predict
housing prices. For this question, use stan to write code and fit
models.

``` r
DC <- read_csv('https://math.montana.edu/ahoegh/teaching/stat532/data/DC.csv')
```

#### a. Exploratory Data Visualization (4 points)

Create at least one figure, preferably more, to display the relationship
between price and other variables in the dataset. Note: your figure
should be better than the large paneled one I presented in class!

Include informative captions, titles, and legends on your figure.

#### b. Model specification (4 points)

The goal is to build the best linear model for predicting housing
prices. Fit a few models and write out the “best” model that you can
find. For now you can assume that the residuals are independent.

If you opt to use a Bayesian approach, make sure to clearly state what
priors you have used.

#### c. Model summary (4 points)

Summarize your model findings. Avoid only using technical statistical
lingo and discuss the results in the context of houses.

#### d. Correlation (2 points)

What are the implications of the following statement from part b? “For
now you can assume that the residuals are independent.”
