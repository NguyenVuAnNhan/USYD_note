Typically, we are interested in hypotheses of the form, $H_0: \beta_1 = 0$ vs $H_1: \beta_1 \neq 0$ or $\beta_1 > 0$ or $\beta_1 < 0$

To do this we use a $t$-test: $$T = \frac{\hat{\beta}_1 - \beta_1}{SE(\hat{\beta}_1)} \sim t_{n-2}$$
where $\hat{\beta}_1$ and $SE(\hat{\beta}_1)$ are given in the R output

![[Pasted image 20240929084849.png]]
### CI for regression coefficients
$100(1-\alpha)\%$ confidence intervals can be constructed for regression coefficients in the usual way: $$\hat{\beta}_1 \pm t^* \cdot SE(\hat{\beta}_1)$$
where $t^*$ is the $\alpha/2$ quantile from a $t$-distribution with $n-2$ degrees of freedom.