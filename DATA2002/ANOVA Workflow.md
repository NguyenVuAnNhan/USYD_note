**Hypothesis**: $H_0: \mu_1 = \mu_2 = ... = \mu_g$ vs $H_1:$ at least one $\mu_i \neq \mu_j$

**Assumptions**: Observations independent, each of the g populations have the same variance, Each of the populations are normally distributed (or sample size large enough for CLT)

**Test statistic**: $T = \frac{T_{MS}}{R_{MS}}$, under $H_0, T \sim F_{g-1, N - g}$ where $g$ is the number of groups.

**Observed test statistic**: $t_0 = \frac{\hat{T_{MS}}}{\hat{R_{MS}}}$ 

**p-value**: $P(T > t_0) = P(F_{g-1,N-g} \ge t_0)$ - Note: always look at upper tail

**Decision**: if p-value less than $\alpha$, we reject the null hypothesis and conclude that the population mean of at least one group is significantly different to the others.
