We can use the [[Using ranks|Kruskal-Wallis test]].

## Friedman test
- The Friedman test is a ranks-based test for a two-way layout:
	- each observation is replaced by its within-block rank
	- a one-way ANOVA F-test is performed on the ranks
- This test can also be performed using either
	- A permutation test approach
	- A $\chi^2$ approximation on an equivalent statistic
- The equivalent statistic is: $$\frac{\text{Treatment sum of squares of the ranks}}{\text{Total sum of squares of the ranks}/n(g-1)}$$
and has an approximate $\chi^2_{g-1}$ distribution under the null hypothesis (all treatments are equivalent)