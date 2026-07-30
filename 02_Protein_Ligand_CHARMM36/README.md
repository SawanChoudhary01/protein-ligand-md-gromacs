# Protein–Ligand Molecular Dynamics Simulation using CHARMM36

## Overview

This project demonstrates a complete protein–ligand molecular dynamics (MD) simulation workflow using GROMACS and the CHARMM36 force field.

The workflow includes protein and ligand preparation, topology generation, solvation, ion addition, energy minimization, equilibration, production molecular dynamics, and trajectory analysis.

---

## System

- **Protein:** 3HTB
- **Ligand:** JZ4
- **Force Field:** CHARMM36 + CGenFF
- **Water Model:** TIP3P
- **Software:** GROMACS

---

## Workflow

1. Protein preparation
2. Ligand parameterization using CGenFF
3. Complex generation
4. Simulation box definition
5. Solvation
6. Ion addition
7. Energy minimization
8. NVT equilibration
9. NPT equilibration
10. Production MD simulation
11. Trajectory analysis

---

## Repository Structure

### input/

Contains cleaned protein, ligand, and simulation parameter (.mdp) files.

### topology/

Contains the system topology, ligand topology, position restraints, and CHARMM36 force field.

### analysis/

Contains representative trajectory analysis files, including RMSD, interaction energy, distance, angle, and potential energy.

### figures/

Contains screenshots and representative simulation figures.

---

## Analysis Performed

- RMSD
- Interaction Energy
- Distance Analysis
- Angle Analysis
- Potential Energy

---

## Skills Demonstrated

- Molecular Dynamics Simulation
- Protein–Ligand System Preparation
- CHARMM36 Force Field
- CGenFF Ligand Parameterization
- Linux Command Line
- GROMACS
- Scientific Data Analysis