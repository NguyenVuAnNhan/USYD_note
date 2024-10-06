### In-sample performance
Resubstitution error rate
- Proportion of observation predicted incorrectly when we predict all the points used to fit the model $$\frac{1}{n}\sum^n_{i=1}(y_i \neq \hat{y}_i)$$

### Out of sample performance
- Sometimes it is impossible to get new data
- k-fold validations
- CV error rate as the average of these k error rates

- Larger k take longer to run but leads to lower prediction error
- Smaller k may lead to higher prediction error
- k is often chosen between 5 and 10