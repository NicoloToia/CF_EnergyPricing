# Computational Finance Energy Finance

**Energy Finance** is the final project for the Computational Finance course (2024-2025). The primary objectives are to calibrate and simulate two models for French electricity futures, as detailed in the file: `Energy_Finance_Report.pdf`.

---

## Project Overview

This project focuses on modeling the dynamics of **energy prices** using two distinct approaches:
- **OU-IG Model**: An Arithmetic Ornstein-Uhlenbeck process with Inverse Gaussian jumps, capturing mean reversion, seasonality, and jumps.
- **OU-Normal Model**: A streamlined Gaussian-based Ornstein-Uhlenbeck model, emphasizing parsimony while preserving key dynamics.

Key components:
- **Spot Price Dynamics**: Incorporating seasonality and stochastic processes.
- **Forward and Swap Pricing**: Deriving analytical expressions under a risk-neutral measure.
- **Model Calibration**: Using optimization methods to fit market data.
- **Monte Carlo Simulation**: Simulating option prices and assessing model robustness.

The dataset includes French power futures with varying delivery periods, analyzed to highlight the relevance of model complexity in commodity markets.

---

## Files and Resources
- **MATLAB Code**: Scripts for model calibration, pricing, and simulation.
- **Project Report**: Detailed methodologies, results, and comparisons between models.
- **Data**: Market prices of futures and other necessary inputs for calibration.
