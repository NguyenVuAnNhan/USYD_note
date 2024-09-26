- When performing $k$ tests, replace $\alpha$ with $\frac{\alpha}{k}$
- This means we simply replace $c(\alpha)$ with $c(\frac{\alpha}{k})$
	- Perform each t-test at "level $\alpha/k$"
	- Construct each confidence interval
- Then the overall performance of the k procedures taken simultaneously is at level $\alpha$
	- The probability of incorrectly rejecting any of the t-test is no more than $\alpha$ (family wise error rate)
	- The probability that all true values are included in the corresponding confidence interval is $1 - \alpha$

## Multiplicity-adjusted p-values
- We can also define the multiplicity-adjusted p-values as k times the unadjusted p-value