Under the null hypothesis of independence, the expected frequencies are $e_{ij} = np_{ij} = np_{i\bullet}p_{\bullet j}$

A large test statistic, $$T = \sum^a_{i=1}\sum^b_{j=1}\frac{(Y_{ij} - e_{ij})^2}{e_{ij}} = \sum^a_{i=1}\sum^b_{j=1}\frac{(Y_{ij} - np_{i\bullet}p_{\bullet j})^2}{np_{i\bullet}p_{\bullet j}}$$
indicates that we should reject $H_0$.

- However, $T$ includes unknown parameters $p_{i\bullet}$ and $p_{\bullet j}$
- Estimate $p_{i \bullet}$ and $p_{\bullet j}$ by $\hat{p}_{i \bullet} = y_{i \bullet}/n$ and $\hat{p}_{\bullet j} = y_{\bullet j}/n$
- Calculate the observed test statistic, $$t_0 = \sum^a_{i=1}\sum^b_{j=1}\frac{(y_{ij} - n\hat{p}_{i\bullet}\hat{p}_{\bullet j})^2}{n\hat{p}_{i\bullet}\hat{p}_{\bullet j}} = \sum^a_{i=1}\sum^b_{j=1}\frac{(y_{ij} - y_{i\bullet}y_{\bullet j}/n)^2}{y_{i\bullet}y_{\bullet j}/n}$$