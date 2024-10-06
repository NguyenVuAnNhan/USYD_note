![[Pasted image 20240929093602.png]]

### Prediction vs confidence interval
Take a regression model with $n$ observations and $p$ regressors, $$Y = X\beta + \epsilon$$
Given a new observation vector $x_0$, the predicted value for that observation is, $$E(Y|x_0) = \hat{y}_0 = x_0' \hat{\beta}$$
A consistent estimator of the variance of this prediction is, $$\hat{Var(\hat{y}_0)} = \hat{\sigma}^2x_0'(X'X)^{-1} x_0$$
where $$\hat{\sigma}^2 = \frac{\sum^n_{i=1}(y_i - \hat{y}_i)^2}{N - k} = \frac{\sum^N_{i=1}r^2_i}{N-k}$$
The forecast error for a particular $y_0$ is $$\hat{e}=y_0 - \hat{y}_0 = (x_0'\beta +\epsilon_0) - \hat{y}_0$$
There is zero covariance between $\epsilon_0$ and $\hat{\beta}$ so, $$Var(\hat{e}) = Var(\hat{y}_0) + Var(\epsilon_0)$$
and a consistent estimator of that is $$Var(\hat{e}) = \hat{\sigma}^2 x_0'(X'X)^{-1}x_0 + \hat{\sigma}^2$$
The $1 - \alpha$ confidence interval will be: $\hat{y}_0 \pm t^*\sqrt{Var(\hat{y}_0)}$, where $Var(\hat{y}_0) = \hat{\sigma}^2x_0(X'X)^{-1}x_0'$

The $1-\alpha$ prediction interval will be wider: $\hat{y}_0 \pm t^*\sqrt{Var(\hat{e})}$
