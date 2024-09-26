- In R, if the data is represented as a data frame with
	- Observations in one column
	- Groups indicated by a factor in another column
Then it is easy to obtain a "random" allocation
- Simply randomly permutate the observation vector, keeping the factor vector fixed
- Do this a large number of times
- The observed proportion of the times the statistic exceeds $t_0$ becomes an estimate of the exact p-value
- This is known as a permutation test