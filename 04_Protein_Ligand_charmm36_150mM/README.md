# Protein–Ligand Molecular Dynamics Simulation Under Physiological Ionic Conditions (150 mM NaCl)

This project demonstrates a complete **protein–ligand molecular dynamics (MD) simulation** using **GROMACS 2023.3** with the **CHARMM36 force field**. Unlike a standard neutralized simulation, this system was prepared under **physiological ionic conditions (150 mM NaCl)** to better represent the biological environment.

---

## Project Overview

This workflow includes:

- Protein preparation
- Ligand preparation
- CHARMM36 topology generation
- Solvation
- Addition of physiological salt concentration (150 mM NaCl)
- Energy minimization
- NVT equilibration
- NPT equilibration
- Production Molecular Dynamics (50 ps)
- Trajectory analysis

---

## Software Used

| Software | Version |
|----------|---------|
| GROMACS | 2023.3 |
| Ubuntu (WSL) | Latest |
| PyMOL | Latest |
| CGenFF | Latest |
| Grace (xmgrace) | Latest |

---

## Simulation Workflow

```
Protein Structure
        │
        ▼
Ligand Preparation
        │
        ▼
Topology Generation
        │
        ▼
Simulation Box
        │
        ▼
Solvation
        │
        ▼
Ion Addition (150 mM NaCl)
        │
        ▼
Energy Minimization
        │
        ▼
NVT Equilibration
        │
        ▼
NPT Equilibration
        │
        ▼
Production MD (50 ps)
        │
        ▼
Trajectory Analysis
```

---

## System Preparation

- Force Field: **CHARMM36**
- Water Model: **TIP3P**
- Temperature: **300 K**
- Pressure: **1 bar**
- Salt Concentration: **150 mM NaCl**
- Production Simulation: **50 ps**

---

## Physiological Salt Environment

Unlike a standard simulation that only neutralizes the system, this project uses:

```bash
gmx genion -neutral -conc 0.15
```

This produces a solution containing approximately **150 mM NaCl**, which better mimics physiological conditions and provides a more realistic electrostatic environment for protein–ligand interactions.

---

## Repository Structure

```
04_Protein_Ligand_150mM_NaCl/
│
├── analysis/
├── figures/
├── input/
├── topology/
└── README.md
```

---

## Analysis Performed

- Temperature
- Pressure
- Density
- Root Mean Square Deviation (RMSD)
- Root Mean Square Fluctuation (RMSF)
- Radius of Gyration
- Hydrogen Bond Analysis
- Solvent Accessible Surface Area (SASA)

---

## Results Summary

The molecular dynamics simulation completed successfully.

Key observations include:

- Stable temperature throughout equilibration.
- Stable solvent density after NPT equilibration.
- Low RMSD indicating structural stability.
- Low RMSF except for flexible loop regions.
- Stable radius of gyration.
- Consistent hydrogen bond network.
- Stable solvent accessible surface area.

These analyses indicate that the protein–ligand complex remained structurally stable during the 50 ps production simulation.

---

## Figures

The `figures/` directory contains:

- Workflow diagram
- Protein–ligand structure
- Temperature
- Pressure
- Density
- RMSD
- RMSF
- Radius of Gyration
- Hydrogen Bonds
- SASA

---

## Folder Description

| Folder | Description |
|---------|-------------|
| `input/` | Input files used for simulation |
| `topology/` | Topology and coordinate files |
| `analysis/` | GROMACS analysis output files |
| `figures/` | Graphs and project figures |

---

## Author

**Sawan Choudhary**

M.Sc. Bioinformatics & Biotechnology

Chanakya University

---

⭐ This project is part of my **GROMACS Molecular Dynamics Simulation** learning series, progressing from basic protein simulations to physiologically relevant protein–ligand systems.