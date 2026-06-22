# Markov-modulated derivative pricing

This is the MATLAB code from an undergraduate summer research project I completed in 2016–17. It explores simulation and European option pricing when volatility is driven by a continuous-time Markov chain.

The repository includes:

- Euler–Maruyama and Milstein simulation for Markov-modulated diffusions;
- absorbing, reflecting and instantaneous-jump boundary conditions;
- occupation-time calculations; and
- an implementation of McKinlay's model for European call options, with a comparison against the published numerical results.

`TestEuroCall.m` is the clearest starting point for the pricing code. The remaining scripts contain the simulation and boundary-condition experiments undertaken during the project.

## Status

This repository is archived historical work. It records an early applied-mathematics project but is not maintained as a current MATLAB package.
