# Protein–Ligand Molecular Dynamics Simulation using AMBER99SB-ILDN and GAFF2

## Overview

This project demonstrates a complete protein–ligand molecular dynamics simulation workflow using GROMACS with the AMBER99SB-ILDN protein force field and GAFF2 ligand parameters generated using ACPYPE.

The workflow includes protein preparation, ligand parameterization, topology generation, solvation, ion addition, energy minimization, equilibration, production molecular dynamics, and trajectory analysis.

---

## System

- **Protein:** 3HTB
- **Ligand:** JZ4
- **Protein Force Field:** AMBER99SB-ILDN
- **Ligand Force Field:** GAFF2 (ACPYPE)
- **Water Model:** TIP3P
- **Software:** GROMACS

---

## Workflow

1. Protein preparation
2. Ligand parameterization using ACPYPE
3. Topology generation
4. Solvation
5. Ion addition
6. Energy minimization
7. NVT equilibration
8. NPT equilibration
9. Production MD simulation
10. Trajectory analysis

---

## Repository Structure

- **input/** – Protein, ligand, and simulation parameter files.
- **topology/** – Topology files and ACPYPE-generated ligand parameters.
- **analysis/** – RMSD, RMSF, SASA, Radius of Gyration, H-bond, and energy analyses.
- **figures/** – Representative figures and screenshots.

---

## Skills Demonstrated

- Molecular Dynamics Simulation
- Protein–Ligand Simulation
- AMBER99SB-ILDN
- GAFF2
- ACPYPE
- GROMACS
- Linux
- Scientific Data Analysis