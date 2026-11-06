#Simulation and Numerical Analysis of SDEs

This is a collection of programming exercises from a master course called Numerical Analysis of Stochastic Differential Equations (NASODE)
together with a direct application of some of the techniques learned there. More precisely, I am modelling the daily log returns of SPY as 
a Geometric Brownian motion and I am estimating its parameters from historical data (2021-2024) and simulating the log returns in 2025. All 
of the relevant statistics are plotted and the simulated returns are compared with the actual returns.

The exercises involve:

- Random-number generation: Box–Muller, acceptance–rejection, Marsaglia polar and inverse-transform sampling for the Cauchy distribution.
- Numerical integration: rectangular and graded rectangular quadrature, including convergence-rate experiments.
- Monte Carlo estimation: estimating expectations and confidence intervals.
- Brownian motion simulation.
- Itô integral approximation and estimation of its first two moments.
- Euler–Maruyama simulation of an SDE, including an empirical strong-convergence experiment.
