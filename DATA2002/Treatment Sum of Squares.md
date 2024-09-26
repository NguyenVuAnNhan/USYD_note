The full "random variable" version of the decomposition looks like
$$\sum^{g}_{i=1}\sum^{n_i}_{j=1}(Y_{ij}-\bar{Y}_{\bullet\bullet})^2 = \sum^{g}_{i=1}\sum^{n_i}_{j=1}(Y_{ij}-\bar{Y}_{i\bullet})^2 + \sum_{i=1}^{g}n_i(\bar{Y}_{i\bullet}-\bar{Y}_{\bullet\bullet})$$

When $H_0$ is true, the final term **must** have a $\sigma^2\chi^2_{g-1}$ distribution

If the true group means are not all equal, the final term will tend to get bigger

That final term is the Treatment Sum of Squares

The ratio $\frac{\Sigma^{g}_{i=1}n_i(\bar{Y}_{i\bullet}-\bar{y}_{\bullet\bullet})}{g-1}$ is the Treatment Mean Square

Generalization of the term $(\frac{\bar{X} - \bar{Y}}{\sqrt{\frac{1}{m}+\frac{1}{n}}})^2$ in the analysis of two-combined-sample variance

Measures the variability of the sample means in a certain sense

$$\text{Treatment Mean Square} = \frac{\text{Treatment SS}}{g-1} = \frac{\Sigma^{g}_{i=1}n_i(\bar{Y}_{i\bullet}-\bar{y}_{\bullet\bullet})}{g-1}$$
