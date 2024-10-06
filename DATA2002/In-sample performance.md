### Decomposing the error
$$\sum^n_{i=1}(y_i - \bar{y})^2 = \sum^n_{i=1}(\hat{y}_i - \bar{y})^2 + \sum^n_{i=1}(y_i - \hat{y}_i)^2$$
where
- Total SS is the total variation in $Y$
- Reg SS is the sum of squares **explained** by the regression line
- Resid SS = Total SS - Reg SS is the variation in $Y$ remain unexplained

### Coefficient of determination $r^2$
The square of correlation coefficient $r^2$ called the coefficient of determination measures the proportion of total variation in $Y$ explained by the linear regression model:

It is "one minus the proportion of variation not explained by the model": $$r^2 = 1 - \frac{\sum^n_{i=1}(y_i - \hat{y}_i)^2}{\sum^n_{i=1}(y_i - \bar{y})^2} = 1 - \frac{\text{Resid SS}}{\text{Total SS}}$$
Hence the coefficient of determination $r^2$ measures the strength of the linear relationship between $x$ and $y$ by the percentage of variation in $y$ explained by the linear regression model in $x$