# Numerical PDE Modeling: Heat Equation

This project implements a finite-difference method for the one-dimensional heat equation.
The goal is to study time-dependent diffusion behavior and numerical stability in a simple PDE model.

## Mathematical Model
∂u/∂t = α ∂²u/∂x²

## Methods
- Explicit finite-difference scheme
- Stability considerations via time-step selection
- Python implementation using NumPy

## Motivation
This project was developed as preparation for graduate study in Applied Mathematics,
with emphasis on PDEs, numerical methods, and computational modeling of physical systems.

## Getting Started
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run `python experiments.py` to see example output

## Example Usage

```python
from heat_equation_fd import solve_heat_equation

u_final = solve_heat_equation(nx=100, nt=500, alpha=0.01, dt=0.0005)
print(u_final)
```

## Files
- `heat_equation_fd.py`: Core finite-difference solver
- `experiments.py`: Example usage and visualization
- `requirements.txt`: Project dependencies

## References
- Brown University Applied Mathematics Graduate Program
- Numerical PDEs, time-dependent diffusion, and stability analysis