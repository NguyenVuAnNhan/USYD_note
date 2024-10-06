- Aim to minimize the sum of squared residuals

### Residual definition
Let, $$r_i = y_i - \hat{y}_i$$
where $\hat{y}_i$ is the fitted value, the value we predict for the $i$th observation given the $i$th predictor value

### Fitting by least squares
The estimated intercept ($\hat{\beta}_0$) and estimated slope ($\hat{\beta}_1$) are found by solving the following optimization problem: $$\text{argmin}_{\beta_0,\beta_1}\sum^{n}_{i=1}(y_i - (\beta_0 + \beta_1 x_i))^2$$
Closed form solutions exist for $\hat{\beta}_0$ and $\hat{\beta}_1$
R does this for us using the lm() function (linear model)
