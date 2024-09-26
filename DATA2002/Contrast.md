Recall our [[Normal model]], we can rewrite this as:
$$Y_{ij}=\mu_i+\epsilon_{ij}$$
where $\epsilon_{ij} \sim N(0, \sigma^2)$ is the error term.

The ANOVA F-test is a test of the hypothesis $H_0: \mu_1 = \mu_2 = ... = \mu_g$

If this hypothesis is "rejected", further analysis is reduced to the study of contrasts.

[[Definition of contrasts]]

[[Distribution of sample contrasts]]

[[Behaviour of contrasts under the null hypothesis]]

This might not be what we want, maybe the non-zero contrasts are not the ones we are interested in. Therefore, we have t-test for individual contrasts.

We can do this by using the corresponding sample contrast and the residual mean square

- The corresponding (random) sample: $$\sum^{g}_{i=1}c_i\bar{Y}_{i\bullet} \sim N(\sum^{g}_{i=1}c_i\mu_i, \sigma^2\sum^{g}_{i=1}\frac{c_i^2}{n_i})$$
- The standardized version: $$\frac{\sum^{g}_{i=1}c_i\bar{Y}_{i\bullet} - \sum^{g}_{i=1}c_i\mu_i}{\sigma\sqrt{\sum^{g}_{i=1}\frac{c_i^2}{n_i}}} \sim N(0, 1)$$
- Replacing $\sigma$ in the denominator with $\hat{\sigma}=\sqrt{\text{Residual MS}} \sim \sqrt{\chi^2_{N-g}/(N-g)}$ (independent of the $\bar{Y}_{i\bullet}$'s) gives $$\frac{\sum^{g}_{i=1}c_i\bar{Y}_{i\bullet} - \sum^{g}_{i=1}c_i\mu_i}{\sigma\sqrt{\sum^{g}_{i=1}\frac{c_i^2}{n_i}}} \sim t_{N-g}$$
- Thus a t-statistic for testing the hypothesis that $\sum^{g}_{i=1}c_i\mu_i = 0$ is $$\frac{\sum^{g}_{i=1}c_i\bar{Y}_{i\bullet}}{\hat{\sigma}\sqrt{\sum^{g}_{i=1}\frac{c_i^2}{n_i}}}$$
which has a $t_{N-g}$ distribution if $\sum^{g}_{i=1}c_i\mu_i = 0$
- Generalizing the two-sample t-statistic

[[Yield]]

[[Confidence interval]]

