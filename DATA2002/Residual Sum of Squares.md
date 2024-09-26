$$\sum_{i=1}^{g}\sum_{j=1}^{n_i}(Y_{ij}-\bar{Y}_{i\bullet})^2=\sum_{i=1}^{g}(n_i-1)S_i^2 \sim \sigma^2 \chi^2_{N-g}$$
noting that $\Sigma^{g}_{i=1}(n_i - 1) = N - g$. This is called the Residual Sum of Squares

Dividing by $N - g$ we obtain an unbiased estimator of $\sigma^2$ , the generalization of pooled estimate of the variance, known as the Residual Mean Square.
$$\hat{\sigma}^2 = \frac{\Sigma^{g}_{i=1}\Sigma^{n_i}_{j=1}(Y_{ij}-\bar{Y}_{i\bullet})^2}{N-g} \sim (\frac{\sigma^2}{N - g})\chi^2_{N-g}$$

