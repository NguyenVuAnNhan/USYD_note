## Kruskal-Wallis test
- Performed by
	- Replacing each observation by its global rank
	- Then compute the F-ratio as usual on the ranks
- A p-value can be obtained by
	- Using a permutation test approach
	- a large-sample $\chi^2$ approximation can also be used

## Kruskal-Wallis test statistic
- Computed as a ratio like the F-test
	- The numerator is exactly the Treatment Sum of Squares of the ranks
	- The denominator is the sample variance of all the ranks
		- The denominator is not random (the same regardless of the allocation)
		- $$T = \frac{\text{Treatment SS of the ranks}}{\text{Variance of all the ranks}}$$
		- When $H_0$ is true, it has an approximate $\chi^2_{g-1}$ 
![[Pasted image 20240924004657.png]]

## Permuted ranks
- The permutation test approach is valid for any "sensible" statistic
	- Assume the same distribution in each group under the null hypothesis
- What of the "sensible statistic"?
	- If data is truly normal, F-statistic makes sense
	- Can also do a permutation test using the Kruskal-Wallis statistic