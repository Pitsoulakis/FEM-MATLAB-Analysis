# 📐 FEM Structural Analysis — MATLAB Implementation

> **Academic Project** — Hellenic Mediterranean University (ELMEPA)  
> Department of Mechanical Engineering

---

## 📌 Overview

Custom **MATLAB** implementation of the **Finite Element Method (FEM)** for structural analysis of mechanical components and structures. The codebase covers 1D and 2D FEM problems from scratch, without relying on commercial FEM solvers.

Building a FEM solver from the ground up provides deep understanding of the numerical foundations behind tools like ANSYS and SolidWorks Simulation.

---

## 🎯 What This Covers

- Assembly of global stiffness matrix from element contributions
- Application of boundary conditions (fixed supports, distributed loads)
- Solution of the linear system K·u = F
- Post-processing: displacement fields, stress and strain computation
- Visualization of deformed shapes and stress distributions

---

## 🧮 Theory Background

The Finite Element Method discretizes a continuous domain into finite elements. For each element, we define a stiffness matrix **Kₑ** based on material properties and geometry. The global system is:

```
K · u = F
```

Where:
- **K** — Global stiffness matrix
- **u** — Nodal displacement vector
- **F** — External force vector

---

## 📂 Elements Implemented

| Element Type | DOF | Application |
|---|---|---|
| Bar / Truss (1D) | 2 | Axial force members |
| Beam (1D) | 4 | Bending & shear |
| Plane Stress (2D) | 8 | Thin plates & frames |

---

## 🛠️ Tools

| Tool | Purpose |
|---|---|
| **MATLAB** | Numerical implementation & visualization |
| **Symbolic Math Toolbox** | Derivation of shape functions |

---

## 🔑 Key Concepts

`FEM` `Finite Element Method` `Structural Analysis` `MATLAB` `Stiffness Matrix` `Numerical Methods` `Solid Mechanics` `Stress Analysis`

---

## 📁 Repository Structure

```
📦 FEM-MATLAB-Analysis
 ┣ 📄 README.md
 ┣ 📂 src/
 ┃  ┣ 📄 assemble_global_K.m    ← Global stiffness assembly
 ┃  ┣ 📄 apply_bc.m             ← Boundary condition application
 ┃  ┣ 📄 solve_system.m         ← Linear system solver
 ┃  ┣ 📄 postprocess.m          ← Stress & strain computation
 ┃  ┗ 📄 plot_results.m         ← Visualization
 ┣ 📂 examples/
 ┃  ┣ 📄 truss_2d.m             ← 2D truss example
 ┃  ┗ 📄 beam_bending.m         ← Cantilever beam example
 ┗ 📂 docs/
    ┗ 📄 theory_notes.pdf
```

> ⚠️ *Code files will be uploaded soon.*

---

## 👤 Author

**Dimitrios Pitsoulakis**  
MEng Mechanical Engineering — Hellenic Mediterranean University  
📧 pitsoulakis01@yahoo.com
