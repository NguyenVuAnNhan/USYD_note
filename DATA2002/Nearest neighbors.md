We can use logistic regression to classify binary observations, this isn't possible when
- We have high class separation in our data
- We have a non-linear combination of predictors influencing our response


We can use decision trees but this approach
- Can be complicated
- May overfit
- Draw boundaries parallel to axes only

### kNN algorithm
- A non-parametric algorithm
- Vote on the class of a new data point by looking at the majority class of the k nearest neighbors

1. Find the k observations in the training data that are closest to $x_0$
2. Denote the set of k closest observations as $D(x_0) \subset (X, y)$ 
3. Define an aggregation function $f$ (majority rules aggregation function) and compute $\hat{y} = f(y)$ for the k values of $y$ in $D(x_0)$ 

- Measure closeness by Euclidean distance

### k-nearest neighbors: advantages
- Easy to understand and implement
- kNN classifier doesn't need to pre-process the training data to make predictions
- Only requires k and the distance metric
- Analytically tractable and simple implementation
- Performance improves as the sample size grows
- Local information, highly adaptive
- Easily parallelized

### k-nearest neighbors: disadvantages
- The distance metric only makes sense for quantitative variables (not categorical predictors)
- Does not scale well and predictions can be slow: computationally intensive when predicting new observations
- Need to store the full data set
- Curse of dimensionality: does not perform well with high dimensional inputs
- Easy to overfit/underfit: Small k can overfit the data. High k tend to smooth out the prediction but may underfit

### Choosing k
- An appropriate choice of k will depend on the application and the data
- Cross validation can be used to optimize the choice of k
- Misclassification rate tends to increases as k increases
- The optimal value of k for minimization of in-sample misclassification is 1