- The residual mean Sq is the estimate of $\sigma^2$, the population variance within each group
- The residual standard error is $\sqrt{\text{Residual Mean Sq}}$, the estimate of $\sigma$, the population standard deviation within each group

- Choosing to see whether there is a difference between treatment 1 and treatment 2, we let their two contrast coefficient be 1 and -1 with the coefficient for the control to be 0

- The observed test statistic for the contrast is $$t_0 = \frac{\sum^{g}_{i=1}c_i\bar{y}_{i\bullet}}{\hat{\sigma}\sqrt{\sum^{g}_{i=1}\frac{c_i^2}{n_i}}}$$
This follows a $t_{N-g}$ distribution if $\sum^{g}_{i=1}c_i\mu_i = 0$, the same degree of freedom from the ANOVA