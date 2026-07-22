# Statics & Engineering Mechanics — Python Projects
### ASEN 2401 | Aerospace Engineering

**Author:** Rhys Owens  
**Course:** AESN 2401 — Statics, Introduction to Mechanics  
**Field:** Aerospace Engineering  
**Tools:** Python 3, NumPy, SciPy, Matplotlib, Jupyter  

---

## Overview

This repository contains computational implementations of 
statics and engineering mechanics concepts from ASEN 2401.
Each project translates a core course topic into working 
Python code, reinforcing theory with computation and 
building engineering intuition through visualization.

Projects progress from fundamental vector algebra through 
equilibrium analysis, truss solving, centroid calculation,
and structural analysis tools.

---

## Environment
Language: Python 3.12
Dependencies: numpy, scipy, matplotlib, jupyter, ipykernel
Platform: Linux (WSL2 / Ubuntu)
Editor: VS Code with Jupyter extension


Setup:
git clone git@github.com:rhys-jones/statics-asen2401.git
cd statics-asen2401
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt


---

## Projects

### 1. Vector Force Calculator
**File:** `vector_force_calculator.ipynb`  
**Course topic:** Vectors and Vector Algebra  

Computes resultant forces in 2D and 3D using NumPy 
vector operations. Calculates magnitude, direction 
angles, direction cosines, and unit vectors.

Outputs:
- Resultant force vector and magnitude (N)
- Direction angle from positive x-axis (degrees)
- 3D direction cosines and angles
- 2D force diagram with all vectors plotted

Key functions: np.linalg.norm(), np.arctan2(),
np.arccos(), np.array()

---

### 2. Moment and Torque Calculator
**File:** `moment_torque_calculator.ipynb`  
**Course topic:** Forces and Moments  

Computes moments about a point in 2D and 3D using 
the cross product M = r x F. Determines magnitude,
direction, and sense of rotation.

Outputs:
- Moment vector and magnitude (N.m)
- Direction of rotation (CW or CCW)
- Force and moment arm diagram

Key functions: np.cross(), np.linalg.norm()

---

### 3. Free Body Diagram Solver
**File:** `fbd_solver.ipynb`  
**Course topic:** Equilibrium in 2D and 3D  

Solves for unknown support reactions using matrix 
form of equilibrium equations (sum F = 0, sum M = 0).

Key functions: np.linalg.solve()

---

### 4. 2D Truss Analyzer (planned)
**File:** `truss_analyzer.ipynb`  
**Course topic:** Trusses, Frames and Machines  

Method of joints truss solver. Computes all member 
forces (tension/compression) using matrix equilibrium.
Color coded visualization of member forces.

---

### 5. Centroid and Moment of Inertia Calculator (planned)
**File:** `centroid_calculator.ipynb`  
**Course topic:** Centroids and Moments of Inertia  

Computes centroids and area moments of inertia for 
composite sections including I-beams, T-beams, 
and channel sections using the parallel axis theorem.

---

### 6. Shear Force and Bending Moment Generator
**File:** `beam_reaction_sfd_bmd.ipynb`  
**Course topic:** Distributed Forces, Shear and Bending  

Generates shear force and bending moment diagrams 
for beams with point loads, distributed loads, 
and applied moments.

---

### 7. Coulomb Friction Analyzer (planned)
**File:** `friction_analyzer.ipynb`  
**Course topic:** Friction  

Models static and kinetic friction on inclined planes 
and wedge problems. Plots friction force vs applied 
load showing static and kinetic regions.

---

## Physics Reference
Resultant force: R = F1 + F2 + ... + Fn
Magnitude: |R| = sqrt(Rx^2 + Ry^2 + Rz^2)
Unit vector: u = R / |R|
Direction cosines: cos(a) = Rx/|R|
Moment (2D): M = r x F = Fxry - Fyrx
Moment (3D): M = r x F (cross product)
Equilibrium (2D): sum Fx = 0, sum Fy = 0, sum M = 0
Parallel axis: I = Ibar + A*d^2


---

## Skills Demonstrated

- Vector algebra and linear algebra (NumPy)
- Engineering mechanics computation
- Scientific visualization (Matplotlib)
- Jupyter notebook analysis and documentation
- Git version control and GitHub portfolio management
- Linux / WSL development environment
- Virtual environment and dependency management

---

## Related Repositories

- [aero-orbital-mechanics](https://github.com/RhysOwens/aero-orbital-mechanics)
  Orbital velocity, Hohmann transfer, delta-V calculations

---

## Keywords

statics, engineering mechanics, vector algebra, 
resultant force, moment of inertia, centroid, 
free body diagram, truss analysis, shear force,
bending moment, Coulomb friction, equilibrium,
numpy, scipy, matplotlib, jupyter, python,
aerospace engineering, ASEN 2401
