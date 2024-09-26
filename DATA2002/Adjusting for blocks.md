For one-way ANOVA, [[ANOVA]]

A third way to write the model is based on expressing each $\mu_i$ as
- An overall mean $\mu$ (with no subscript) plus
- an adjustment $\alpha_i$ for i-th level of the treatment: $$\mu_i = \mu + \alpha_i$$
- This leads to the model, for $i = 1,...,g, j=1,...,n_i$ $$Y_{ij} = \mu + \alpha_i + e_{ij}$$
- Note there are now $g+1$ mean parameters: $\mu, \alpha_1,..., \alpha_g$
	- We created a new parameter

## An extra constraint
- In fact, due to how $\mu$ is defined, the $\alpha_i$ obey a certain constraints
- The overall mean is defined as some kind of weighted average of the $\mu_i$: $$\mu = \sum^{g}_{i=1}w_i\mu_i$$
- Then each $\alpha_i = \mu_i - \mu$
- Necessarily: $$\sum^g_{i=1}w_i\alpha_i = 0$$
- Knowing $g-1$ of the $\alpha_i$ also means knowing the final one

## Estimating these new parameter
- A common choice for the weighted average is: $$\mu = \frac{1}{N}\sum^{g}_{i=1}n_i\mu_i = \frac{\sum^g_{i=1}n_i\mu_i}{\sum^g_{i=1}n_i}$$
- Which is the expectation of the grand mean $\bar{Y}_{\bullet \bullet}$
- This can be estimated using the observed grand mean $\bar{y}_{\bullet \bullet}$
- Each $\alpha_i$ represents the difference between each group mean and the overall mean
	- Estimated by the difference $$\hat{\alpha_i} = \bar{y}_{i\bullet} - \bar{y}_{\bullet \bullet}$$
