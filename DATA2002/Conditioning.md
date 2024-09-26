- A common tool in testing is to condition on an "ancillary" statistic
	- "ancillary statistic" just means a statistic that does not tell us anything useful

- A familiar example is the sign test:
	- We condition on the number $N$ of non-zero differences

## Conditioning on the combined sample
- If we combine all the groups into one combined sample, the remaining data tells us nothing about the differences between the groups (what we need)
- In this sense, this combined sample is a ancillary statistic
- Once we condition on the combined sample, the only remaining randomness is the allocation of observations to groups
- Under the null hypothesis of no differences between groups, all possible allocations are equally likely
- We get an exact conditional probability: $$\frac{N!}{n_1!n_2!...n_g!}$$ (the probability to get a particular allocation of N values into g groups of size $n_1, n_2, ..., n_g$)

$$P(T \ge t_0 | \text{combined sample})=\frac{\text{number of allocations with T >= t0}}{\text{total number of allocations}}$$
- Unless the sample size is very small
	- The total number of allocations is MASSIVE
	- Computing this is not feasible
- We can estimate this proportion by taking a sufficiently large random sample from the population of all possible allocations