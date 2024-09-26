- The weighted average decomposition introduced earlier for the two-sample t-test is a special case of a more general decomposition.

- Total sum of Squares
$$\sum_{i=1}^{g}\sum_{j=1}^{n_i}(y_{ij}-\bar{y}_{\bullet\bullet})^2=\text{Residual SS + Treatment SS}$$
which is $(N-1)$ times the *combined* sample variance of all observations
$$\hat{\sigma}^2_0=\frac{\text{Total SS}}{N-1}=\frac{\Sigma_{i=1}^{g}\Sigma_{j=1}^{n_i}(y_{ij}-\bar{y}_{\bullet\bullet})^2}{N-1}$$
Compare with the $i$-th group's sample variance:
$$s^2_i=\frac{1}{n_i - 1}\Sigma^{n_i}_{j=1}(y_{ij}-\bar{y}_{i\bullet})^2$$
