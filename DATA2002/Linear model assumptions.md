### Linearity - the relationship between Y and x is linear
- Important as if violated, the predictions are likely systematically wrong
- Plot y against x to see if the relationship is approximately linear
- Look at a plot of residuals against x:
	- Residuals should be symmetrically distributed above and below zero
	- A curved pattern is evidence for non-linearity

### Independence - all errors are independent of each others
- Usually dealt with during experiment design
- Aim to design so that observations are not related to one another
- If we don't have a random sample, my estimates might be biased
- Often occurs in time series data

### Homoskedascity - errors have constant variance for all i
- Same spread
- Constant error variance is important to ensure the hypothesis tests to give valid results
- Violations (heteroskedascity) make it difficult to estimate true standard deviation
- Also give too much weight to small subset of the data
- Check via plots of residuals versus x

### Normality - errors follow a normal distribution
- Violations of normality can compromise our inferences
- Check via Q-Q plots of the residuals
- Extreme values may provide the most useful information

- The last three can be written succinctly as $\epsilon_i \sim N(0, \sigma^2)$
