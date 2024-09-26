In summary:
- The residual sum of squares always follows a $\sigma^2 \chi^2_{(n-1)(g-1)}$ distribution (regardless of whether the null hypothesis is true or not);
- if the null hypothesis of no treatment effect is true, the treatment sum of squares follows a $\sigma^2 \chi^2_{(n-1)(g-1)}$ distribution

Therefore, if the null hypothesis is true, the F-ratio $$\frac{\text{Treatment mean square}}{\text{Residual mean square}} \sim \frac{\chi^2_{g-1}/(g-1)}{\chi^2_{(n-1)(g-1)}/(n-1)(g-1)} \sim F_{g-1, (n-1)(g-1)}$$
Otherwise, it tends to take larger values, just like the one-way ANOVA