The model is $$Y_{ij} = \mu + \alpha_i + \beta_j + e_{ij}$$
where $$\mu = \text{overall mean}$$
$$\alpha_i = \text{adjustment for electrode type i for i = 1,2,...,g}$$
$$\beta_j = \text{adjustment for subject j for j = 1,2,...,n}$$
and n is the common sample (block) size and the $e_{ij}$'s are idd $N(0, \sigma^2)$
- So each $Y_{ij}$ has a possibly different expectation $\mu_{ij} = \mu + \alpha_i + \beta_j$ but these have an additive structure:
	- The $ng$ different means are explained by $g+n-1$ free parameters