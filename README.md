# ARIMA models for NIST

These are ARIMA models that represent the process detailed at the [NIST Statistics handbook](https://www.itl.nist.gov/div898/handbook/pmc/section4/pmc445.htm). The code is all Python using
Pandas, Statsmodels and Matplotlib. 


The results agree reasonably with the R results published in the handbook.

## R auto.arima
The results are compared with the `auto.arima` package from R.

## Prophet
We also compare the results of hand made simulation with the results of the [Prophet](https://github.com/facebook/prophet) library.

