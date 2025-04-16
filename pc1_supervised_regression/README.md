# PC1 – Supervised Learning without Neural Networks

This notebook is the first assignment of the course *Scientific Machine Learning for Numerical Analysis* (APM-51053-EP) at École Polytechnique. It introduces supervised learning from a scientific computing perspective, focusing on classical regression techniques that do not involve neural networks.

## Topics Covered

- **Linear regression**  
  Using normal equations and QR factorization to solve least squares problems.

- **Nonlinear regression**  
  Implementation of Gauss–Newton’s method with QR decomposition to minimize a nonlinear error functional.

- **Trigonometric interpolation**  
  Construction of interpolants on the periodic interval using the Fast Fourier Transform (FFT).

## Mathematical Foundations

The goal is to approximate a function \( f \in L^2(D) \) based on data \( \{(x_i, y_i)\}_{i=1}^n \), where \( y_i = f(x_i) \), using a model \( \hat{f}(\cdot; w) \) from a finite-dimensional space \( \hat{F} \subset L^2(D) \). The notebook explores how to:

- Minimize the **training error** \( E_T(\hat{f}) = \frac{1}{n} \sum_{i=1}^n |\hat{f}(x_i) - y_i|^2 \)
- Estimate the **generalization error** and discuss its decomposition (approximation, generalization, optimization)
- Apply **QR decomposition** to solve both linear and nonlinear least squares problems
- Use **FFT-based trigonometric interpolation** to recover smooth periodic signals from discrete samples
