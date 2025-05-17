The MSVAR MSN-Burr model extends the traditional Markov Switching Vector Autoregressive (MSVAR) framework by incorporating the Modified Skew Normal Burr distribution to better capture asymmetric and heavy-tailed characteristics in multivariate time series data. This makes it particularly useful for modeling complex dynamic systems with insufficient standard Gaussian assumptions.

##Key Features
Robust to non-normality: Handles skewness and heavy tails in data effectively.

Regime switching: Models multiple latent states with dynamic transitions.

Multivariate autoregression: Captures dependencies across multiple time series variables.

Bayesian estimation: Utilizes advanced sampling techniques such as No-U-Turn Sampler (NUTS) for parameter inference.

Applications
The MSVAR MSN-Burr model is particularly suited for:

Financial time series analysis with regime changes and asymmetric shocks.

Biomedical signal processing, such as EEG data analysis for detecting seizure states.

Environmental and economic data exhibiting nonlinear dynamics and structural breaks.

Repository Contents
Implementation scripts in Stan and R for model estimation and simulation.

Example datasets and simulation scenarios.

Detailed documentation on model specification, estimation procedures, and diagnostics.

Visualization tools for posterior analysis, regime classification, and forecast evaluation.

Getting Started
To run the MSVAR MSN-Burr model:

Install required software: R, Stan, and dependencies.

Load example data or provide your own multivariate time series.

Configure model parameters and priors as needed.

Run the estimation script using NUTS sampler.

Analyze outputs including posterior distributions, regime probabilities, and forecast accuracy.
