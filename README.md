# MAE 263F — Homework 1: Spring Network Simulation  
**Author:** Yuchen Wang (Ph.D. in Mechanical Engineering, UCLA)  
**Date:** October 2025  

---

## 📘 Project Overview
This repository contains the implementation and report for **Homework 1** of *MAE 263F: Mechanics of Flexible Structures & Soft Robots*.  
The goal is to simulate 2-D spring networks using different numerical integration schemes:

- **Implicit Euler method** for stiff dynamic systems  
- **Explicit Euler method** for comparison of stability  
- **Newmark–β method** to eliminate artificial numerical damping  

All simulations are performed for the spring networks (a) and (b) defined in the homework statement:contentReference[oaicite:1]{index=1}.

---

## 🚀 How to Run the Code
### Option 1 — Run via Jupyter Notebook
1. Open the `.ipynb` file in Jupyter Lab or VS Code.  
2. Execute all cells in order to generate the plots and figures.  

### Option 2 — Run via Python Script
```bash
python Homework1.py
