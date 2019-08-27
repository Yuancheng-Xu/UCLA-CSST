For longitudinal data (n,T,p), replace each time series (that is, for one patient, one feature) with its slope (and variance, residual) and fit a regular Randon Forest or Fuzzy Forest.

Essentially this is a dimension reduction technique. It turns out that when n is not big enough, slope tree fails completely to identify true features. 

When n is big enough and the true model is linear, slope tree is fine but when true model is nonlinear, slope true is not so good. 