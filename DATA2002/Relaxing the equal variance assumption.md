- We can drop the common variance by consider all pairwise Welch tests and apply a Bonferroni correction
- $$T = \frac{\bar{X} = \bar{Y}}{\sqrt{\frac{S^2_X}{m}+\frac{S^2_Y}{n}}}$$
- We can take the smallest p-value for the global hypothesis that all means are the same
`oneway.text(data ~ factor)`
