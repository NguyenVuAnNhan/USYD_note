- Under our new parametrization, each treatment difference is still naturally estimated using the corresponding treatment level mean difference
- For example:
	- $\alpha_1$ using $\bar{y}_{1\bullet} - \bar{y}_{\bullet \bullet}$
	- $\alpha_1 - \alpha_2$ using $\bar{y}_{1\bullet} - \bar{y}_{2 \bullet}$

- Under this two-way model, the corresponding random mean difference is distributed as $$\bar{Y}_{1\bullet} - \bar{Y}_{2\bullet} \sim N(\alpha_1 - \alpha_2, \frac{2\sigma^2}{n})$$
since all treatment groups have a common sample size n