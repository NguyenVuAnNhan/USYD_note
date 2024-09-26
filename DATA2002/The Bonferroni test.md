If we are doing all pairwise comparisons across g groups, there will be $\binom{g}{2}$ pairs

If none of the tests end up rejecting (after adjustment) then this means the smallest individual p-value (corresponding to the most significant pairwise difference) was greater than $\alpha / \binom{g}{2}$

Therefore the p-value for the Bonferroni test is simply $\binom{g}{2}$ times the smallest unadjusted p-value

If this test rejects, we can post hoc identify which comparison are significant by identifying which adjusted p-values are less than $\alpha$
