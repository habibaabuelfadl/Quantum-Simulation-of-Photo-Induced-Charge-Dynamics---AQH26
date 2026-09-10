# Quantum Simulation of Photo-Induced Charge Dynamics: From Ethylene to Photosynthesis

A quantum simulation study of **photo-induced charge dynamics in ethylene (C₂H₄)**, investigating how molecular geometry affects its electronic structure and excited-state behavior.

This project was developed as part of the **Quantum Computing Hackathon at Bibliotheca Alexandrina**, held from **September 6–8, 2026**, where our team achieved **3rd Place** 🥉.

## Project Overview

We investigated **C₂H₄ (ethylene)** at two molecular configurations:

* **Equilibrium geometry**
* **Twisted geometry**

The goal was to explore the electronic structure and low-lying excited states using quantum algorithms, while examining the effect of realistic quantum-device noise.

## Methodology

###  Variational Quantum Eigensolver (VQE)

We used **VQE** to estimate the molecular ground-state energy by optimizing a parameterized quantum circuit with respect to the molecular Hamiltonian.

###  Quantum Subspace Expansion (QSE)

We applied **QSE** on top of the VQE ground state to access excited states and estimate excitation energies, allowing us to investigate the electronic transitions associated with photo-induced processes.

###  Equilibrium vs. Twisted Geometry

The molecular geometry was varied to study how twisting the ethylene molecule changes its electronic structure and affects the calculated excitation energies.

###  Noise Simulation

We introduced quantum-device noise into the simulations to investigate how hardware imperfections affect the calculated molecular properties.

###  Error Mitigation

Error mitigation techniques were applied to reduce the impact of noise and improve the reliability of the quantum simulation results.

###  Classical Reference

The quantum results were compared with **classical electronic-structure calculations** to evaluate the accuracy of the quantum approach.

## Workflow

```text
C₂H₄ Molecular Geometry
          ↓
     PySCF / Qiskit
          ↓
   Molecular Hamiltonian
          ↓
         VQE
          ↓
    Ground State
          ↓
         QSE
          ↓
   Excited States
          ↓
   Noise Simulation
          ↓
   Error Mitigation
          ↓
 Classical Comparison
```

## Tools & Technologies

* **Qiskit**
* **Qiskit Nature**
* **PySCF**
* **Python**
* **VQE**
* **QSE**
* **Quantum Noise Simulation**
* **Error Mitigation**
* **Quantum Chemistry**

## Team

Developed collaboratively by:

* **Habiba Abu-Elfadl**
* **Merna Mohamed** 
* **Reem Ali** 
* **Mohamed A. AbdAlfattah** 
* **Mohamed Maged** 

## Achievement

🏆 **3rd Place — Quantum Computing Hackathon**
📍 Bibliotheca Alexandrina
📅 September 6–8, 2026

---

*This project explores the potential of quantum computing for molecular simulation and quantum chemistry, using ethylene as a simplified model for photo-induced charge dynamics relevant to photosynthetic processes.*
