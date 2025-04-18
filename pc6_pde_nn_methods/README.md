# PC6 – Advanced Neural PDE Methods

This notebook is the sixth practical assignment of *Machine Learning for Scientific Computing and Numerical Analysis*. It explores a variety of neural‑network‑based solvers for PDEs beyond basic PINNs.

## Topics Covered

- **PINN Setup**  
  Defining the network class and generating 1D & 2D collocation grids.

- **Deep Ritz Method**  
  Variational formulation: training networks to minimize the energy functional.

- **PINNs with Hard Boundary Conditions**  
  Solving elliptic PDEs by encoding Dirichlet conditions directly into the trial function.

- **Viscous Burgers Equation**  
  - Soft enforcement of BCs  
  - Hard‑encoded initial & boundary conditions  

- **Fourier Features**  
  Tackling high‑frequency elliptic problems:  
  - Classical PINN approach  
  - Enhanced embedding with Fourier feature mappings