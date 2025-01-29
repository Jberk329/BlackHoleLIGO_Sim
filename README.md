# BlackHoleLIGO_Sim
Research on a modified Einstein–Cartan theory with torsion, scalar fields, and spinor fields. Simulating a black hole scenario in a 5D extension and analyzing potential gravitational-wave signals relevant to LIGO.
## Overview

This repository contains code for simulating black hole scenarios in a 5D extension of a modified Einstein–Cartan theory with torsion, scalar fields, and spinor fields. The goal is to analyze potential gravitational-wave signals relevant to LIGO.

## Code Structure

The `SimulationCode.nb` Mathematica notebook includes:

- Definition of the manifold, metric, torsion tensor, scalar, and spinor fields.
- Construction of a custom Lagrangian with Ricci scalar, torsion terms, scalar potential, and Dirac spinor.
- Variation to obtain field equations.
- Numerical solutions to the resulting PDEs under initial and boundary conditions representing black hole formation or perturbations.
- Code sections demonstrating `DefManifold` and `DefMetric` from xAct, torsion degrees of freedom (`MyTorsion[...]`), scalar and spinor definitions (`phi[]`, `psi[]`), and the PDE system (modified Einstein equations, torsion field equations, Klein-Gordon for `phi[]`, Dirac-like for `psi[]`).
- Preliminary results plotting gravitational waveforms or metric perturbations for comparison with LIGO data.

## Usage Instructions

1. Open the `SimulationCode.nb` file in Mathematica.
2. Ensure the xAct package is installed and loaded.
3. Execute the notebook cells in sequence to define the manifold, metric, and fields.
4. Modify initial and boundary conditions as needed for different scenarios.
5. Run the numerical solver to obtain results.
6. Analyze the output plots and data for insights into gravitational-wave signals.

## Citation

If you use this code in your research, please cite the relevant literature on modified Einstein–Cartan theory and LIGO gravitational-wave detection.
