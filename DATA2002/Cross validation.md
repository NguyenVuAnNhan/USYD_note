### k-fold cross-validation estimation
- Data randomly divided into k subsets of nearly equal size
- Estimate model by leaving one subset out
- Use estimated model to predict the left out subset
- Compute error rates on the left out subset
- Repeat k times
- Average the error rate

Bias-variance tradeoff: lower k give larger bias but smaller variance. Computationally intensive