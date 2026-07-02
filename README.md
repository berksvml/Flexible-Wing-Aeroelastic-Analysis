# Flexible Wing Aeroelastic Analysis

**Master of Science Thesis Project**

A comprehensive aeroelastic analysis of a composite flexible wing combining Finite Element Analysis (FEA) and Computational Fluid Dynamics (CFD).

---

## Project Overview

This project investigates the aeroelastic behavior of a composite flexible wing developed as part of my Master's thesis in Aerospace Engineering.

The workflow integrates structural modelling, modal analysis, transient structural simulations and aerodynamic CFD analyses to evaluate the interaction between aerodynamic loads and structural deformation.

The project was developed using ANSYS Mechanical and ANSYS Fluent.

---

## Objectives

- Design a realistic composite wing structure
- Develop an FEM model for structural analysis
- Investigate natural vibration characteristics
- Perform transient structural analysis under gust loading
- Generate CFD simulations for aerodynamic loading
- Evaluate pressure distribution and aerodynamic forces
- Assess the aeroelastic response of the wing

---

# Geometry

## Airfoil

![Airfoil](figures/01_airfoil_profile/NACA23012Profile.png)

The wing is based on the NACA 23012 airfoil.

---

## Structural Design

![Structure](figures/02_structural_design/InternalStructure.png)

The internal structure consists of:

- Front I-shaped spar
- Rear C-shaped spar
- Composite skin
- Longitudinal stringers
- Reinforcing ribs

---

# FEM Pre-processing

## Material Assignment

![Materials](figures/03_fem_preprocessing/MaterialAssignment.png)

Composite materials were assigned to the wing components according to the structural design.

---

## Contact Definitions

![Contacts](figures/03_fem_preprocessing/Contacts.png)

Bonded contacts were defined between structural components.

---

## Finite Element Mesh

Global mesh

![Mesh](figures/03_fem_preprocessing/Fem.png)

Root section

![Root Mesh](figures/03_fem_preprocessing/FemRoot.png)

---

# Modal Analysis

The first natural vibration mode of the flexible wing.

![Modal](figures/04_modal_analysis/ModalAnalysis.png)

---


# CFD Pre-processing

## Computational Domain

![Enclosure](figures/06_cfd_preprocessing/CFD_Enclosure.png)

---

## CFD Mesh

![Mesh](figures/06_cfd_preprocessing/DomainMEsh.png)

Wing surface mesh

![Surface Mesh](figures/06_cfd_preprocessing/WingMeshFluent.png)

---

# CFD Results

## Pressure Distribution

![Pressure](figures/07_cfd_results/StaticPressure.png)

---

## Pressure Coefficient

![Cp](figures/07_cfd_results/Cp.png)

---

## Velocity Distribution

![Velocity](figures/07_cfd_results/VelocityMagnitude.png)

---

## Lift

![Lift](figures/07_cfd_results/LifForce_0.55.png)

---

## Drag

![Drag](figures/07_cfd_results/DragFroce_0.55.png)

---

## Lift Coefficient

![CL](figures/07_cfd_results/CL_0.55.png)

---

## Drag Coefficient

![CD](figures/07_cfd_results/CD_0.55.png)

---

## Solver Convergence

![Residuals](figures/07_cfd_results/ScaledResiduals_0.55.png)

---

# Validation

The transient structural loading was generated using a validated 1-cos gust profile.

![Validation](figures/08_validation/COS-gust-amplitude-experimental-results-compared-with-an-ideal-signal-k-005-and-d.png)

---

# Software

- ANSYS Mechanical
- ANSYS Fluent
- SpaceClaim
- Composite Pre/Post Processing

---

# Engineering Topics

- Aeroelasticity
- Structural Dynamics
- Finite Element Analysis
- CFD
- Aerodynamics
- Composite Structures
- Modal Analysis
- Transient Structural Analysis

---

# Repository Contents

```
cad/
    Structural wing geometry
    CFD wing geometry

figures/
    Airfoil
    Structural model
    FEM preprocessing
    Modal analysis
    Transient analysis
    CFD preprocessing
    CFD results
    Validation
```

---

# Note

This repository presents selected engineering results from my Master's thesis.

To protect the originality of the research, the complete thesis document and ANSYS project files are not publicly available. The repository focuses on demonstrating the engineering workflow, modelling approach, and technical competencies developed throughout the project.
