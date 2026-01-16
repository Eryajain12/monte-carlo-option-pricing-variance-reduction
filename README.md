# Variance Reduction Techniques in Monte Carlo Option Pricing

This project studies the efficiency of variance reduction methods in Monte Carlo simulation for option pricing under the Black–Scholes framework.

## Techniques Implemented
- Standard Monte Carlo
- Antithetic Variates
- Control Variates
  - European Call as control
  - Geometric Asian Call as control

## Options Priced
- European Call Option
- Arithmetic Asian Call Option

## Key Results
- Antithetic variates significantly reduce variance for both European and Asian options
- Control variates outperform antithetic methods when a strongly correlated control is available
- Geometric Asian control achieves near-optimal variance reduction (ρ ≈ 0.999)

## Files
- `Variance Reduction Techniques.ipynb` – Full Python implementation & experiments
- `Variance Reduction Techniques.pdf` – Detailed report with theory, results, and plots

## Tools & Concepts
Python, NumPy, Monte Carlo Simulation, Black–Scholes, Variance Reduction, Quantitative Finance
