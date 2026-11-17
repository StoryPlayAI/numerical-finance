# numerical-finance
Numerical Methods in Finance

A Python project exploring numerical methods in financial applications, with a focus on numerical stability, convergence, accuracy, and computational efficiency.

Overview

This project investigates the mathematical foundations and computational performance of numerical algorithms used in financial modeling, portfolio optimization, and derivatives pricing.

The objective is to understand the numerical properties, limitations, and trade-offs of different methods through theoretical analysis and reproducible computational experiments.

Modules

1. Factor Regression: QR vs. Normal Equations

Analysis of numerical stability in linear least-squares problems.

* Ordinary Least Squares using normal equations.
* QR decomposition.
* Matrix conditioning and numerical errors.
* Accuracy and computational performance.

2. Portfolio Optimization: Markowitz and Covariance Shrinkage

Investigation of covariance estimation and its impact on portfolio optimization.

* Mean-variance framework and minimum-variance portfolios.
* Sample covariance estimation.
* Covariance shrinkage and Ledoit-Wolf estimation.
* Portfolio weight sensitivity and conditioning.
* Out-of-sample risk analysis.

3. Implied Volatility: Newton-Raphson vs. Bisection

Comparison of numerical root-finding methods for implied volatility estimation.

* Black-Scholes option pricing.
* Newton-Raphson method.
* Bisection method.
* Convergence analysis.
* Numerical accuracy and robustness.

4. Option Pricing: Quadrature vs. Monte Carlo vs. FFT

Comparative study of numerical methods for European option pricing.

* Numerical quadrature.
* Monte Carlo simulation.
* Variance reduction techniques.
* Fast Fourier Transform pricing.
* Accuracy, convergence, and computational efficiency.

Project Structure

numerical-finance/
├── src/
│   └── numerical_finance/
│       ├── regression/
│       ├── portfolio/
│       └── options/
├── experiments/
├── tests/
├── reports/
├── figures/
├── pyproject.toml
└── README.md

Installation

Clone the repository:

git clone https://github.com/StoryPlayAI/numerical-finance.git
cd numerical-finance

Create and activate a virtual environment:

python3.12 -m venv .venv
source .venv/bin/activate

Install the required dependencies:

python -m pip install -e ".[dev]"

Experiments

Each module will include a Jupyter Notebook containing reproducible numerical experiments, performance comparisons, and visualizations.

The experiments will evaluate numerical accuracy, convergence, stability, and computational cost.

Technical Report

A technical report, Numerical Methods in Finance: A Comparative Study, will document the mathematical foundations, experimental methodology, numerical results, and conclusions.

The report will be available in the reports/ directory upon completion.

Project Status

Under development.

The project is currently in its initial development stage. Numerical implementations, experiments, and documentation will be added progressively.
