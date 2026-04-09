# Shear Wave Propagation in the Brain: FEA in COMSOL Multiphysics
This project presents a systematic finite element (FE) investigation into how domain geometry, boundary treatments, and material parameters influence shear-wave motion in fluid-saturated, brain-like media. Designed to evaluate the assumptions underlying Magnetic Resonance Elastography (MRE) inversion, the study characterizes wave dynamics in complex poroelastic environments.

## Key Features
- Physics-Based Modeling: Implements Biot’s theory of poroelasticity, fully coupling solid displacement and pore fluid pressure to capture the biphasic nature of brain tissue.
- Geometry Benchmark: Comparative analysis between a 3D cube, 2D square, and 2D circle to isolate dimensional effects and geometric scattering from intrinsic material dissipation.
- Boundary Artifact Mitigation: Utilizes Perfectly Matched Layers (PML) and periodic boundary conditions to eliminate reflected energy, providing coherent wave fronts for spatial signature analysis.
- Parametric Sensitivity Study: A batch simulation of 108 scenarios per geometry exploring the impact of permeability, porosity, and fluid viscosity on wave penetration and phase velocity.

## Technical Summary
- Software: COMSOL Multiphysics.
- Analysis Tools: Python for high-throughput data extraction, non-linear least squares regression for attenuation coefficients, and calculation of global coefficients of variation.
- Key Finding: Hydraulic permeability is the primary determinant of fluid-solid coupling and energy dissipation, while circular geometries introduce systematic "geometric scattering" that can bias traditional plane-wave stiffness estimates.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------
Note: This repository is currently under construction as implementation files are being migrated from development environments. For a comprehensive overview of the system architecture, mathematical background, and simulation results, the full project report is available in the repository.
