# MAE 263F — Homework 1: Spring Network Simulation  
**Author:** Yuchen Wang (Ph.D. in Mechanical Engineering, UCLA)  
**Date:** October 2025  

---


## How to Run the Code
### Run via Jupyter Notebook
1. Open the `.ipynb` file in Jupyter Lab or VS Code.  
2. Execute all cells in order to generate the plots and figures.  

---

## File Descriptions
### `Homework1.ipynb`
Implements the **Implicit Euler method** for simulating the spring network (b).  
It initializes nodal positions, computes spring forces and Jacobians, and performs Newton–Raphson iterations to solve for equilibrium at each time step.  


---

### `Spring_Network_a_Newmark.ipynb`
Implements the **Newmark–β method** (`β = 1/4`, `γ = 1/2`) for both spring networks (a) and (b).  
This notebook demonstrates how the Newmark–β integration eliminates the artificial damping observed in the implicit Euler results.  
It simulates up to `t = 10 s` and `t = 100 s`, and plots the time history of the free nodes to illustrate stable oscillations.

---

### `Homework1_Wang.pdf` / `Homework1.pdf`
The final **report** summarizing all results and analyses for Homework 1.  
It includes:
- Pseudocode and derivation of the governing equations  
- Comparison of explicit vs. implicit Euler methods  
- Time step selection discussion  
- Analysis of numerical damping  
- Validation using the **Newmark–β** simulation results with plots for networks (a) and (b)
