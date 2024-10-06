### Construction
1. Choosing the number of decision trees to grow and number of variable to consider when splitting each node
2. For each tree, randomly selecting the rows of the data with replacement (bootstrapping)
3. When growing each tree, randomly selecting the appropriate number of variables at each split from the bootstrapped data (without replacement)
4. Building a decision tree at each split
5. Replace steps 2-4 a large number of time
6. Predict by majority rule