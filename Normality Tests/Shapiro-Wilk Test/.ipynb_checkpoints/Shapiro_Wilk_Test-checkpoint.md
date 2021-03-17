This section lists statistical tests that you can use to check if your data has a Gaussian distribution.

# Shapiro-Wilk Test

The Shapiro-Wilk test evaluates a data sample and quantifies how likely it is that the data was drawn from a Gaussian distribution.

In practice, the Shapiro-Wilk test is believed to be a reliable test of normality, although there is some suggestion that the test may be suitable for smaller samples of data, e.g. thousands of observations or fewer.

The shapiro() SciPy function will calculate the Shapiro-Wilk on a given dataset. The function returns both the W-statistic calculated by the test and the p-value.

Objective: Tests whether a data sample has a Gaussian distribution.

## Assumptions

Observations in each sample are independent and identically distributed (iid).

## Interpretation

H0: the sample has a Gaussian distribution.
H1: the sample does not have a Gaussian distribution.