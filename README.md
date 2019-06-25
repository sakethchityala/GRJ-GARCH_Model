## Estimating the Parameters of a GARCH Model

*In this project I will estimate the paramentes of a GJR-GARCH(1,1,1) model with a constant mean. The volatility dynamics in a GRJ-GARCH model are given by*

$σ_{t}^2=ω+\sum_{i=1}^pα_iε_{t-i}^2+\sum_{j=1}^oγ_jε_{t-j}^2I_{t-j}+\sum_{k=1}^qβσ_{t-k}^2$

$\sigma$
### GJR-GARCH(1,1,1)

## $$σ_{t}^2=ω+(α+γI_{t-1})ε_{t-1}^2+βσ_{t-1}^2$$

Paremeters

To estimate the parameters, it is necessary to:
1. Produce some starting values
2. Estimate the parameters using (quasi-) maximum likelihood (QML)
3. Compute standard errors using a “sandwich” covariance estimator
