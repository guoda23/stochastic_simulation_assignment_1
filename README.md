# Computing the Area of the Mandelbrot Set

## Overview

This code investigates the quality of five different sampling techniques in estimating the area of the Mandelbrot set. The set is based on the iterative application of the equation: fc(z) = z2 + c. The Monte Carlo Integration method is used to estimate the area. The five sampling techniques examined are Pure Random, Latin-hypercube, Orthogonal sampling, Edge function and RBF weighting. By modifying the number of iterations and samples, we can reach a plausible area of the Mandelbrot set without much computing power. This results in the findings that Orthogonal Sampling has the fastest convergence rate, but does not converge to the pseudo-true value. Latin Hypercube and Pure Random Sampling converged slower. The Importance Sampling methods were the slowest, but the RBF weighting function does converge to the pseudo-true value.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation

```bash
git clone https://github.com/guoda23/stochastic_simulation_assignment_1.git
cd stochastic_simulation_assignment_1
pip install -r requirements.txt
```

## Usage

- Open mandelbrot_area_estimation.ipynb
- Select a Python interpreter
- Press run all 