# BLISK Aeroelasticity Study: ACTIVE Test Rig

This repository contains a comprehensive computational aeroelasticity study focused on flutter prediction and aerodynamic damping evaluation for a single-stage compressor. The core objective was to benchmark CFD simulation results against experimental data obtained from the ACTIVE test rig.

### Project Overview & Toolchain
* **Objective:** To accurately replicate experimental turbomachinery data using advanced CFD solvers, analyzing the differences in aerodamping and flow fields between linear and non-linear aerodynamic models.
* **Software Stack:** * **CAD & Meshing:** CATIA V5 for geometry preparation and AutoGrid for high-quality structured turbomachinery meshing.
  * **CFD Solvers:** Various internal proprietary solvers (including HADES) were utilized to handle both steady and unsteady aeroelastic simulations.
  * **Post-processing:** Tecplot and ParaView for advanced 3D flow field visualization and data extraction.

### Research Scope
* **Linear Aerodynamic Simulations:** Comprehensive modal analysis and flutter evaluation. The first presentation details the baseline aerodynamic domain definition, steady-state solutions, and the unsteady acoustic wave propagation causing blade bending modes. The simulated aerodynamic damping showed an excellent correlation with the ACTIVE experimental data.
* **Non-Linear Aerodynamic Simulations:** A deeper dive into the influence of aerodynamic non-linearities on compressor damping. The repository includes one of the main progress reports from this phase, which highlights the initial non-linear results, mesh refinement iterations (including tip-gap integration), and domain modifications to benchmark the solver against experimental (EXP) and ITP reference data.
