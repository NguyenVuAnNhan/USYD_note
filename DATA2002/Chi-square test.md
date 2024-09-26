Hypothesis: $H_0$: assumed proportion vs $H_1$: unequal or one-sided

Assumption: Expected values > 5, IID observations

Test statistics: $t_0 = \Sigma^{k}_{i=1}\frac{(y_i - e_i)^2}{e_i}$

P-value; $P(\chi^2_{df} > t_0)$ with $df$ dependent on the situation

Conclusion: if p-value is lower than threshold, reject, else accept.

Discrete distributions changes:
$T = \Sigma^{k}_{i=1}\frac{(Y_i-np_i)^2}{np_i}$
where i = 1,2,...,k iterates over the distinct outcomes

However, the model parameters $\theta_1, \theta_2,...,\theta_h$ are usually unknown and have to be estimated. When that happens, we switch $\hat{p}$ for $p$ and let $df = k - 1 - h$ with $h$ as the number of parameters estimated.