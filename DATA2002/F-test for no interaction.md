- Under the full model, the random variable version of the residual sum of squares $$\sum^{a}_{i=1}\sum^{b}_{j=1}\sum^{n}_{k=1}(Y_{ijk} - \bar{Y}_{ij\bullet})^2 \sim \sigma^2\chi^2_{ab(n-1)}$$
since
- The total sample size is $N = abn$
- The number of groups is $g = ab$
- The degrees of freedom for residuals is $N - g = abn - ab = ab(n-1)$

- For the no interaction model $$\sum^{a}_{i=1}\sum^{b}_{j=1}\sum^{n}_{k=1}(Y_{ijk} - \bar{Y}_{i\bullet\bullet} - \bar{Y}_{\bullet j \bullet} + \bar{Y}_{\bullet\bullet\bullet})^2 \sim \sigma^2\chi^2_{(a-1)(b-1)}$$
- The F-statistic for testing the null hypothesis of no interaction is $$\frac{\text{Interaction Mean Square}}{\text{(full model) Residual Mean Square}} = \frac{\text{(Int. SS)/[(a-1)(b-1)]}}{\text{(full model Residual SS)/[ab(n-1)]}} \sim F_{(a-1)(b-1), ab(n-1)}$$
If the null hypothesis of no interactions is true