A sensible test statistic considers the ratio of these two ways of estimating $\sigma^2$
$$\frac{\text{Treatment Mean Square}}{\text{Residual Mean Square}} = \frac{\Sigma^g_{i=1}n_i(\bar{Y}_{i\bullet}-\bar{Y}_{\bullet\bullet})^2/(g-1)}{\hat{\sigma}^2}$$
$$=\frac{\Sigma^{g}_{i=1}n_i(\bar{Y}_{i\bullet}-\bar{Y}_{\bullet\bullet})^2/(g-1)}{\Sigma^g_{i=1}\Sigma^{n_i}_{j=1}(Y_{ij}-\bar{Y}_{i\bullet})^2/(N-g)}$$
$$\sim \frac{\chi^2_{g-1}/(g-1)}{\chi^2_{N-g}/(N-g)}$$
$$\sim F_{g-1,N-g} \text{ under } H_0$$

- Denominator is always an unbiased estimator of $\sigma^2$ regardless of whether $H_0$ is true or not

- The numerator is only an unbiased estimator of $\sigma^2$ if $H_0$ is true, otherwise it tends to get bigger