# A Tour of Time Series Analysis

Talk will be given to PyData San Francisco on 13 August 2016. Summary:

- Covers several time series methods, with a focus on score-driven models
- Uses the PyFlux library to perform analysis with these models.
- Contains a simple NFL prediction model - a starting point for those getting into sports analytics.

## Corrections

- I said dropout approximates a 'Bayesian model': I meant to say it approximates Bayesian inference (the model itself isn't Bayesian or frequentist per say). See https://arxiv.org/abs/1506.02142.
- I mispoke and said "metrics like KL divergence" - while KL looks like a mathematical metric, it doesn't actually satisfy the triangle inequality so isn't a metric in the strict sense; see the literature on Bregman divergences.
- I often said overround instead of overflow in the Q&A; I used to be a sports quant so perhaps the former comes more naturally to my mind...


