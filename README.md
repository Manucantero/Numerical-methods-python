# Numerical Methods & Dynamical Systems in Python

Collection of mathematical modeling, numerical analysis, and scientific computing projects implemented in Python, covering chaotic dynamical systems, iterative root-finding dynamics, and piecewise polynomial interpolation.

## Projects

### 1. Lorenz Attractor — Butterfly Effect Simulation (`/lorenz-attractor`)
- **Mathematical Model:** Numerical integration of the coupled nonlinear ordinary differential equations (ODEs) defining the Lorenz system.
- **Chaos & Sensitivity:** Visualizes 3D phase-space trajectories and demonstrates sensitive dependence on initial conditions.

### 2. Basins of Attraction (`/basins-of-attraction`)
- **Iterative Methods & Convergence:** Analyzes the convergence behavior of numerical root-finding/iterative methods across the complex or real plane.
- **Fractal Boundaries:** Computes and color-maps the regions of initial conditions that converge to each attractor, revealing intricate boundary structures.

### 3. Parametric Spline Interpolation (`/spline-interpolation`)
- **Piecewise Polynomial Approximation:** Reconstructs complex 2D contours (a Pokémon silhouette) from discrete control points using spline interpolation.
- **Smoothness & Continuity:** Ensures continuous derivatives across segments to produce smooth parametric curves without Runge's phenomenon.

## Tech Stack

- **Language:** Python 3
- **Scientific & Plotting Libraries:** NumPy, SciPy, Matplotlib
- **Environment:** Jupyter Notebook / Python Scripts

## How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/Manucantero/numerical-methods-python.git](https://github.com/Manucantero/numerical-methods-python.git)
   cd numerical-methods-python
   ```

2. Install the required dependencies:
   ```bash
   pip install numpy scipy matplotlib
   ```

3. Navigate to any project folder (`lorenz-attractor`, `basins-of-attraction`, or `spline-interpolation`) and run the script or Jupyter Notebook to generate the plots.
