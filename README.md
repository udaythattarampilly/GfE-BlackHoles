# GfE-BlackHoles
Mathematica code and numerical files for " Spherically symmetric black holes in Gravity from entropy"
Udaykrishna Thattarampilly, Yunlong Zheng, and Vishnu Kakkat**, *"Spherically symmetric black holes in Gravity from Entropy and spontaneous emission"*, Physical Review D (2026).
[arXiv:2602.13694](https://doi.org/10.48550/arXiv.2602.13694)

## Abstract
We investigate static and dynamical spherically symmetric black hole solutions within the Gravity from Entropy (GfE) framework. The code in this repository solves the modified vacuum field equations, establishes consistency with strong-field astrophysical observations (S2 star and EHT).

## Repository Content

The `notebooks/` directory contains the following Wolfram Mathematica (.nb) files:

1. **`schwarzchild solution.nb`**
   - Implements the modified Einstein equations (Eq. 15).
   - Solves for metric functions $A(r)$ and $B(r)$ using the asymptotic series expansion (Eq. 16, 17).
   - **Generates Figure 1**: Comparison between numerical solutions and the analytic Schwarzschild limit.

2. **`precession constraint on beta.nb`**
   - Calculates the relativistic periapsis shift $\delta\phi$ (Eq. 25).
   - Performs numerical integration using S2 star orbital parameters ($a \approx 12,500r_S, e \approx 0.8846$).
   - **Generates Figure 2**: Precession factor $f_{SP}$ as a function of the coupling parameter $\beta$.

3. **`lensing constraint on beta.nb`**
   - Solves for the photon sphere radius $r_{ps}$ (Eq. 30) and critical impact parameter $b_{crit}$.
   - Computes the angular shadow diameter $\theta_{sh}$ for Sagittarius A*.
   - **Generates Figure 3**: Observational bounds on $\beta$ using EHT data.

## Software Requirements
- **Wolfram Mathematica**: Tested on version 13.0 and above.
- No external packages are required.
