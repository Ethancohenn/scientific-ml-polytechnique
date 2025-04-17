# PC1 – Supervised Learning without Neural Networks

This notebook is the first assignment of the course *Scientific Machine Learning for Numerical Analysis* (APM-52009-EP) at École Polytechnique. It implements and benchmarks classical regression methods—both linear and nonlinear—using custom algorithms and built‑in libraries.

## Topics Covered

- **Synthetic Data Generation**  
  Creation of toy datasets for different models with controllable noise.

- **Linear Least Squares**  
  Formulation via normal equations and solution using a custom QR factorization (Gram–Schmidt), compared against `np.linalg.lstsq`.

- **Nonlinear Least Squares (Gauss–Newton)**  
  Iterative solver that linearizes the model at each step, solves the resulting linear system via QR, and updates parameters until convergence.

- **Full Newton’s Method**  
  Use of exact Hessian and gradient to perform quadratic convergence updates, with comparison to Gauss–Newton in terms of speed and robustness.

- **Performance & Error Analysis**  
  Benchmarking custom vs. built‑in routines to assess convergence behavior.
