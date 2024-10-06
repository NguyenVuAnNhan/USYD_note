[[Sub-spaces]]

### PCA
- Principal component analysis produces a low-dimensional representation of a dataset. It finds a sequence of linear combinations of the variables that have maximum variance and are mutually uncorrelated
- It is an unsupervised learning method

Why
- We have too many predictors for a regression, we can use the first few principal components. PCA regression
- Understanding relationships between variables - similar to a correlation matrix
- Data visualization - plot a small number of variables more easily than a large number of variables

### PCA: definition
The first principal component of a set of variables $x_1, x_2, ..., x_p$ is the linear combination $$z_1 = \phi_{11}x_1 + \phi_{21}x_2 + ... + \phi_{p1}x_p$$
that has the largest variance such that $$\sum^p_{j=1}\phi^2_{j1} = 1$$
The elements $\phi_{11},...,\phi_{p1}$ are the loadings of the first principal component.

### PCA: Geometry
- The loading vector $\phi_1 = [\phi_{11},...,\phi_{p1}]$' defines direction in feature space along which data vary most.
- If we project the n data points $x_1, ..., x_n$ onto this direction, the projected values are the principal component scores $z_1 = [z_{11}, ..., z_{n1}]'$
- The second principal component is the linear combination $z_{i2} = \phi_{12}x_{i1} + \phi_{22}x_{i2} + ... + \phi_{p2}x_{ip}$ that has maximal variance among all linear combinations that are uncorrelated with $z_1$.
- Equivalent to constraining $\phi_2$ to be orthogonal (perpendicular) to $\phi_1$. And so on.
- There are at most $min(n-1, p)$

PCA projects data onto a new coordinate system where the principal component vectors are orthogonal to each other. The first PC tries to account for as much variation as possible in the data.