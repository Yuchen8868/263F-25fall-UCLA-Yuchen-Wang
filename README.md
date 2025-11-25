# MAE 263F — Homework 5: Static Response of a Thin Plate Using Discrete Shells
**Author:** Yuchen Wang (Ph.D. in Mechanical Engineering, UCLA)  
**Date:** November 2025  
---
## 📘 Project Overview
The objective of Homework~5 is to model the static deformation of a thin rectangular
plate subject to gravity loading using a discrete shell formulation.
The plate, of dimensions \(l \times w\) and thickness \(h\), is discretized into a
triangulated mesh, and its stretching and bending energies are computed according to
linearized elasticity. The left edge of the plate is clamped, while the right edge is free
to deform under the plate's self–weight.

To obtain the static (steady) configuration, the discrete shell model is evolved in time
using dynamic relaxation with damping. The plate is advanced via implicit time stepping
until the motion settles according to a prescribed steady–state criterion. Once the
steady configuration is reached, the tip displacement at the centerline of the free
edge is extracted as
\[
\delta_{\text{plate}}(t) = z_{\text{tip}}(t) - z_{\text{tip}}(0).
\]

Finally, the steady displacement obtained from the discrete plate simulation is compared
against the classical Euler--Bernoulli cantilever beam prediction,
\[
\delta_{\text{EB}} = \frac{q\,l^{4}}{8 Y I},
\qquad
q = \rho A g,
\]
allowing assessment of the agreement between the full plate model and the simplified 1D
beam theory.

This assignment integrates shell mechanics, numerical integration, dynamic relaxation,
and deformation visualization, while providing a direct comparison between discrete
shell modeling and Euler--Bernoulli beam theory.
---

## How to Run the Code
### Run via Jupyter Notebook
1. Open the `.ipynb` file in Jupyter Lab or VS Code.
2. Execute all cells in order to generate the plots and figures.

---

## File Descriptions
### Homework5.ipynb
This Jupyter Notebook contains the full implementation of the implicit solver for the beam simulation described in Homework 5.

---

### Homework5_Wang.pdf
The final report summarizing all results and analyses for Homework 5.
