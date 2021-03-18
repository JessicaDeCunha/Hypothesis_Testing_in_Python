# Kwiatkowski-Phillips-Schmidt-Shin

The Kwiatkowski Phillips Schmidt Shin tests whether a time series is trend stationary or not.

## Assumptions

Observations in are temporally ordered.

## Interpretation

- Null Hypothesis (H0): If failed to be rejected, it suggests the time series has a unit root, meaning it is non-stationary. It has some time dependent structure.

- Alternate Hypothesis (H1): The null hypothesis is rejected; it suggests the time series does not have a unit root, meaning it is stationary. It does not have time-dependent structure.


- p-value > 0.05: Fail to reject the null hypothesis (H0), the data has a unit root and is non-stationary.
- p-value <= 0.05: Reject the null hypothesis (H0), the data does not have a unit root and is stationary.

# Results

stat=0.257, p=0.100
Probably not Stationary