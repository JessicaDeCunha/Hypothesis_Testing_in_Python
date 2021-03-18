# Augmented Dickey-Fuller Unit Root Test

The Augmented Dickey-Fuller test determines whether a time series has a unit root. The intuition behind a unit root test is that it determines how strongly a time series is defined by a trend.

## Assumptions

Observations in are temporally ordered.

## Interpretation

- Null Hypothesis (H0): If failed to be rejected, it suggests the time series has a unit root, meaning it is non-stationary. It has some time dependent structure.

- Alternate Hypothesis (H1): The null hypothesis is rejected; it suggests the time series does not have a unit root, meaning it is stationary. It does not have time-dependent structure.

We interpret this result using the p-value from the test. A p-value below a threshold (such as 5% or 1%) suggests we reject the null hypothesis (stationary), otherwise a p-value above the threshold suggests we fail to reject the null hypothesis (non-stationary).

- p-value > 0.05: Fail to reject the null hypothesis (H0), the data has a unit root and is non-stationary.
- p-value <= 0.05: Reject the null hypothesis (H0), the data does not have a unit root and is stationary.

# Results

Likely Stationary

ADF Statistic: -7.158368
p-value: 0.000000
Critical Values:
	1%: -3.500
	5%: -2.892
	10%: -2.583