# Variational Quantum Eigensolver (VQE) for Molecular Simulations

This project implements **Variational Quantum Eigensolver (VQE)** algorithms to simulate molecular ground-state energies using **Cirq** and **OpenFermion**. It demonstrates how quantum computing techniques can be applied to **computational chemistry**, focusing on molecules such as H₂ and HF.

## Features
- Constructed **quantum circuits (ansatz)** with rotation and entangling gates to model molecular wavefunctions.  
- Transformed **molecular Hamiltonians** into qubit operators using the **Jordan-Wigner transformation**.  
- Used classical **optimization algorithms (COBYLA)** to minimize energy estimates from quantum circuits.  
- Compared VQE results with exact diagonalization solutions to analyze **accuracy and efficiency**.  
- Explored **molecular potential energy surfaces (PES)** by calculating energies across multiple bond lengths.  
- Visualized results using **matplotlib**, plotting energy curves and comparing quantum vs. classical methods.  

## Tech Stack
- **Python**, **Cirq**, **OpenFermion**, **NumPy**, **SciPy**, **Matplotlib**

## Purpose
This project provides a hands-on demonstration of **quantum algorithms for chemistry**, illustrating how quantum simulation can be applied to calculate molecular energies and study chemical systems beyond classical computational limits.
