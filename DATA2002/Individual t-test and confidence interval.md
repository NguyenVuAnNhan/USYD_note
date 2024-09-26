Assume we're testing with a significant level $\alpha$
- We estimate the standard error $\sigma \sqrt{\frac{2}{n}}$ by using $\hat{\sigma}$
- Suppose $c(\alpha)$ satisfies $P(-c(\alpha) \le t_{(n-1)(g-1)} \le c(\alpha)) = 1 - \alpha$
- An individual level $\alpha$ t-test for comparing groups 1 and 2 would therefore reject for $$\frac{|\bar{y}_{i \bullet} - \bar{y}_{2 \bullet}|}{\hat{\sigma}\sqrt{\frac{2}{n}}} > c(\alpha)$$
- An individual $100(1 - \alpha)\%$ confidence interval for $\alpha_1 - \alpha_2$ would be given by $$\bar{y}_{i\bullet} - \bar{y}_{2\bullet} \pm c(\alpha)\hat{\sigma}\sqrt{\frac{2}{n}}$$