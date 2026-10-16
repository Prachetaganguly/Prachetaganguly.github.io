---
layout: single
title: "Rotational Effects on Wake Transition in a Circular Rotating Cylinder at Low Reynolds Numbers"
permalink: /projects/rotational-wake-transition/
author_profile: true
project_order: 3
presented_on: "12th October, 2025"
---

## Project Overview

This research paper presents a comprehensive two-dimensional numerical investigation analyzing the fluid dynamics and aerodynamic force transitions of an incompressible, laminar, and unsteady flow past a single rotating circular cylinder. The project establishes vital insights into wake stability control mechanisms with wide-ranging industrial applicability, including vortex-induced vibration (VIV) suppression in structural engineering, marine riser optimization, rotating machinery design, and advanced aerodynamic flow control.

The computational domain utilizes a concentric, unconfined circular configuration with a radius of 50D to strictly minimize artificial boundary constraints. Simulations were performed across low Reynolds numbers (Re = 100, 200, and 300) while systematically varying the cylinder's non-dimensional angular velocity (ω) from 0 to 6 to evaluate the stabilizing influence of body rotation on the surrounding flow field. The numerical workflow solved the two-dimensional governing continuity and Navier-Stokes equations utilizing a structurally refined mesh layout consisting of 120,000 quadrilateral elements.

A major scholarly contribution of this study is the identification and characterization of a **dual critical rotational speed (ω<sub>cr</sub>)** phenomenon across all investigated Reynolds numbers. As the rotation rate increases, the traditional asymmetric Von Kármán vortex shedding is suppressed at a lower critical speed (ω<sub>cr1</sub> ≈ 3). Beyond this value, a creeping recirculation zone develops on the upper side of the cylinder, altering surface pressure profiles and generating a downward directional force due to the predominated Magnus effect. Further rotation reintroduces minor wake instabilities until reaching a higher rotation threshold - defined as the second critical omega (ω<sub>cr2</sub> ≈ 6) - where the wake becomes fully stabilized and the vorticity concentrates completely along a single shear layer.

---

### [Project Presentation]({{ '/files/Sharanya_Incotherm_paper-246.pptx' | relative_url }})

---

## Key Methodologies & Toolkit

* **Numerical Simulation Framework:** Computational Fluid Dynamics (CFD) / Finite Volume Method (FVM)
* **Mesh & Geometric Modelling:** Concentric Circular Computational Domain (50D Boundary Radius), Grid Independence Evaluation (120,000 Quadrilateral Grid Elements)
* **Data Processing & Post-Processing:** Tecplot / MATLAB (Vorticity Contours, Streamline Verification, Aerodynamic Force Tracking)
* **Core Concepts:** Low-Reynolds Fluid Mechanics, Wake Transition Dynamics, Vortex-Induced Vibrations (VIV), Magnus Effect, Aerodynamic Force Coefficients (Cd, Cl, Cp vs. θ)
