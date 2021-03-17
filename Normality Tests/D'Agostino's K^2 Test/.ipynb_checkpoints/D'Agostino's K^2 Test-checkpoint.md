This section lists statistical tests that you can use to check if your data has a Gaussian distribution.

# D'Agostino's K^2 Test

The D’Agostino’s K^2 test calculates summary statistics from the data, namely kurtosis and skewness, to determine if the data distribution departs from the normal distribution.

- **Skew** is a quantification of how much a distribution is pushed left or right, a measure of asymmetry in the distribution.

- **Kurtosis** quantifies how much of the distribution is in the tail. It is a simple and commonly used statistical test for normality.

Objective: Tests whether a data sample has a Gaussian distribution.

## Assumptions

Observations in each sample are independent and identically distributed (iid).

## Interpretation

H0: the sample has a Gaussian distribution.
H1: the sample does not have a Gaussian distribution.

## Results

Statistics=0.102, p=0.950
Sample looks Gaussian (fail to reject H0)

The p-value is interpreted against an alpha of 5% and finds that the test dataset does not significantly deviate from normal.