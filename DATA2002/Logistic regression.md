For linear regression we have $$Y = \beta_0 + \beta_1x_1 + \beta_2x_2 + ... + \beta_px_p + \epsilon$$
where $\epsilon \sim N(0, \sigma^2)$
- Conditional on the vector of predictor variable, the dependent variable $Y$ also follows a normal distribution $$Y_i|x_i = N(x_i'\beta, \sigma^2)$$
- If the dependent variable $Y$ is binary, a linear regression doesn't work so well and we typically use logistic regression instead

It's natural to model it as a Bernoulli random variable, $$Y_i|x_i \sim \text{Bernoulli}(p(x_i, \beta))$$
where the probability that $Y_i = 1$ is given by some function of our predictors, $p(x_i, \beta)$
We need $p(x_i, \beta)$ to be in $[0, 1]$ and for it to depend on the linear combination of our predictors.
A common choice is the logistic function, $$p(x_i, \beta) = \frac{exp(x_i'\beta)}{1 + exp(x_i'\beta)}$$
- We estimate $\hat{\beta}$ using iteratively reweighted least squares

### Logit function
$$logit(p) = log(\frac{p}{1-p})$$