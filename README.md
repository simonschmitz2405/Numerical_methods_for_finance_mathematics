# Quantitative Finance: Numerical Methods & Stochastic Simulation

A collection of Python-based numerical methods for stochastic calculus and derivative valuation. This repository contains implementations of advanced Monte Carlo techniques and numerical approximation schemes for solving Stochastic Differential Equations (SDEs) applied to financial derivatives.

## Mathematical Implementations

The repository focuses on the computational aspects of financial mathematics, specifically addressing discretization errors, variance reduction, and the pricing of European options under geometric Brownian motion.

### 1. The Euler-Maruyama Method (`Euler_Maruyama_method.ipynb`)
- Implementation of the Euler-Maruyama numerical scheme for approximating the solutions of Stochastic Differential Equations (SDEs).
- Evaluates the strong and weak convergence properties of the discretized paths.

### 2. Standard Monte Carlo Pricing (`Error_Approximation_European_call_option_via_SMC.ipynb`)
- Standard Monte Carlo (SMC) engine for the valuation of European Call Options.
- Includes rigorous error approximation, confidence interval construction, and computational complexity analysis as a function of sample size.

### 3. Multilevel Monte Carlo (`Multilevel_Monte_Carlo.ipynb`)
- Implementation of the Multilevel Monte Carlo (MLMC) estimator to drastically reduce the computational complexity of SDE simulations.
- Demonstrates variance reduction techniques by simulating paths across varying levels of discretization grid refinement, optimizing the trade-off between bias and computational cost.

## Repository Structure

```text
├── Error_Approximation_European_call_option_via_SMC.ipynb
├── Euler_Maruyama_method.ipynb
├── Multilevel_Monte_Carlo.ipynb
└── README.md
```

## Usage

The implementations are provided as interactive Jupyter Notebooks to explicitly show the mathematical derivations alongside the Python execution.

To explore the numerical methods locally:

```bash
git clone [https://github.com/simonschmitz2405/numerical_methods_for_finance_mathematics.git](https://github.com/simonschmitz2405/numerical_methods_for_finance_mathematics.git)
cd numerical_methods_for_finance_mathematics
jupyter notebook
```

Prerequisites:
`numpy`, `matplotlib`, `scipy`

