- We thus have 2 models:
	- The full model where $\mu_{ij}$ is unrestricted
	- The no interaction null hypothesis where $\mu_{ij} = \mu + \alpha_i + \gamma_j$

- Under each model, each observation $y_{ijk}$ is decomposed into two parts:
	- A fitted value $\hat{\mu}_{ij}$
	- a residual $y_{ijk} - \hat{\mu}_{ij}$

- Under the full model $\hat{\mu}_{ij} = \bar{y}_{ij\bullet}$ the mean of the (i,j)-th treatment combination
- Under the no interaction model, the fitted value is $$\hat{\mu}_{ij} = \hat{\mu} + \hat{\alpha}_i + \hat{\gamma}_j = \bar{y}_{i\bullet\bullet} + \bar{y}_{\bullet j \bullet} - \bar{y}_{\bullet \bullet \bullet}$$
[[Residual sum of squares for each model]]
