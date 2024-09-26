![[Pasted image 20240925071005.png]]
Under the null hypothesis of homogeneity, $p_{11} = p_{21}, p_{12} = p_{22}, p_{13} = p_{23}$

We don't know $p_{ij}$, so estimate using category proportions, $\hat{p}_{ij} = \frac{y_{\bullet i}}{n}$

Under $H_0$, the expected counts are, $$e_{ij} = n_i\hat{p}_{ij} = y_{i\bullet}\frac{y_{\bullet i}}{n} = \frac{\text{Row i total} \cdot \text{Column j total}}{\text{Overall total}}$$
and the test statistic is, $T = \sum^{r}_{i=1}\sum^{c}_{j=1}\frac{(Y_{ij}-e_{ij})^2}{e_{ij}} \sim \chi^2_{(r-1)(c-1)}$ approximately