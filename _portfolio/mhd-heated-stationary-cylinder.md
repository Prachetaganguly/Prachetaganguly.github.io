---
layout: single
title: "Magnetohydrodynamic (MHD) Flow and Heat Transfer Around a Heated Stationary Cylinder"
permalink: /projects/mhd-flow-cylinder/
author_profile: true
presented_on: "11th October, 2025"
project_order: 2
---

## Project Overview

This research presents a rigorous two-dimensional numerical investigation analyzing the impact of a transverse magnetic field (B₀) on magnetohydrodynamic (MHD) flow and convective heat transfer around a stationary circular cylinder. The study addresses critical engineering performance factors across metallurgy, nuclear reactor cooling systems, and specialized aerospace thermal management workflows where controlling boundary layer separation and structural drag is paramount.

Simulations were carried out utilizing a finite volume method (FVM) solver framework within ANSYS Fluent for an electrically conducting, incompressible fluid across three distinct operational regimes marked by moderate to high Reynolds numbers (Re = 1,000, 10,000, and 100,000) over a wide parameter matrix of Hartmann numbers (Ha = 0 to 200, extended up to 500 for Re = 100,000). The numerical methodology utilized a structurally refined grid featuring 170,000 quadrilateral elements optimized through grid independence evaluations, and was validated extensively against established literature.

The results show that the introduced Lorentz force acts as a strong stabilizer against fluid instabilities, suppressing asymmetric vortex shedding and forcing unsteady wake configurations to transition into symmetric recirculation bubbles. Damping these flow separations alters localized boundary layer traits; it steepens near-wall temperature gradients to systematically increase average Nusselt numbers (Nu), while simultaneously driving up the total drag coefficient (Cd) due to the compounding effect of electromagnetic resistance forces.

---

### [Project Presentation]({{ '/files/Pracheta_Incotherm_paper-251.pptx' | relative_url }})

---

## Key Methodologies & Toolkit

* **Numerical Simulation Framework:** ANSYS Fluent (Finite Volume Method Solver)
* **Discretization Algorithms:** QUICK (Quadratic Upstream Interpolation for Convective Kinetics) scheme for convective terms, SIMPLE algorithm for pressure-velocity coupling
* **Mesh Generation & Processing:** Grid Independence Testing (170,000 quadrilateral grid layers)
* **Core Concepts:** Fluid Mechanics, Magnetohydrodynamics (MHD), Navier-Stokes with Lorentz Force terms, charge conservation (the divergence of current density is zero), Convective Heat Transfer (Nu, Cp, Cd, Cl evaluation)
