A natural extension of simple linear regression that incorporates multiple explanatory variables. It has the general form, $$Y = \beta_0 + \beta_1x_1 + \beta_2x_2 + ... + \beta_px_p + \epsilon, \text{ where } \epsilon \sim N(0, \sigma^2)$$
Often it's convenient to write the model in matrix format, $$Y = X\beta + \epsilon$$
![[Pasted image 20240929090155.png]]

### Least square solution
$$\hat{\beta} = (X'X)^{-1}X'y$$

### Interpretation
The estimated coefficients ($\hat{\beta}$'s) are now interpreted as "conditional on" the other variables - each $\beta_i$ reflects the predicted change in $y$ associated with a one unit increase in $x_i$, holding the other variables constant (marginal effect)

### In-sample performance
The $r^2$ value has the same interpretation: proportion of total variability in $Y$ explained by the regression model.