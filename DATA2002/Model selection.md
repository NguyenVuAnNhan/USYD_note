### Stepwise selection
#### Backward variable selection
1. Start with model containing all possible explanatory variables
2. For each variable in turn, investigate the effect of removing variable from current model
3. Remove the least informative variable
4. Go to step 2, stop when all variables are important

### The Akaike information criterion
- AIC is the most widely known and used model selection method
$$AIC = n log(\frac{\text{residual sum of squares}}{n})+2p$$
- The smaller the AIC, the better
- Differences of one or two AIC values can be regarded as equal

### Forward variable selection
1. Start with model containing no explanatory variable
2. For each variable in turn, investigate effect of adding that variable
3. Add the most significant variable
4. Go to step 2, stop when no more significant variable to add