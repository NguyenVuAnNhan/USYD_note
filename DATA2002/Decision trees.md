- Determines the predicted outcome based on series of questions and conditions

### Model selection
- There is a complexity parameter that can be used to determine if a proposed new split sufficiently improves the predictive power or not
- A choice is made to keep or prune a proposed branch
- Default is that a branch should decrease error by 1%

### Weakness
- Can become complex very quickly
- Selected tree might be very sensitive to the complexity penalty
- Can only make decisions parallel to axes