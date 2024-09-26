- When no single group is special or notable, each pairwise difference is equally interesting, we can consider each pairwise difference as a contrast of interest
- In this case,
	- A t-statistic can be constructed for each pairwise difference
	- A t-based confidence interval can be constructed for each pairwise population difference (contrast)

Individual 95% confidence interval: $\bar{y}_{i\bullet} - \bar{y}_{h\bullet}$ has the standard error $\hat{\sigma}\sqrt{\frac{1}{n_i}+\frac{1}{n_h}}$ (essentially a two sample t-test)

- Probability that all confidence intervals include the real results:
	- Bonferroni correction: take original significance level and divide by the number of tests being performed
	- Tukey's method: when sample sizes are equal can be used, more conservative when sample sizes are unequal
	- Scheffe's method: We choose the special multiplier $$t_{Sch}^*(\alpha)=\sqrt{(g-1)F_{g-1,N-g}(\alpha)}$$
	- And construct confidence intervals for all contrasts according to $$\sum^{g}_{i=1}c_i\bar{Y}_{i\bullet} \pm t_{Sch}^*(\alpha)\hat{\sigma}\sqrt{\sum^g_{i-1}\frac{c_i^2}{n_i}}$$
- Then the probability that all sample contrasts include their true population values is exactly $1 - \alpha$
- We are comparing each contrast t-statistic to the $\sqrt{*(g-1)F}$
- Any which exceeds that critical value is significant in this "simultaneous" sense
- The smallest such p-value is exactly the ANOVA F-test p-value