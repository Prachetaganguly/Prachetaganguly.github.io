---
layout: single
title: "Accelerating Premixed H₂–Air Combustion Simulations Using Neural ODE"
permalink: /projects/neural-ode-combustion/
author_profile: true
presented_on: "10th July 2026"
project_order: 1
---

## Project Overview

I worked on this project during my internship at IIT Gandhinagar, under the guidance of Professor Shubhangi Bansude. The project addresses the extreme computational bottlenecks associated with traditional reactive flow calculations. By integrating a Neural Ordinary Differential Equation (Neural-ODE) framework coupled with a Detailed Kinetic Mechanism (DKM) into ANSYS Fluent, this project replaces computationally intensive chemical kinetics solvers with high-fidelity scientific machine learning (SciML) surrogates.

Using the PyFluent API, the workflow automates the simulation of 1-D premixed hydrogen-air combustion inside a closed chamber to establish high-fidelity reference datasets validated against the San Diego mechanism. The trained Neural-ODE architecture significantly accelerates chemical source-term and localized heat transfer rate predictions. To ensure physical consistency, an encoder-decoder validation loop is incorporated to monitor conservation laws, dynamically reverting to direct-kinetics model calls if prediction margins drift, while successfully reconstructing temperature profiles from enthalpy conservation.

### Poster Preview

<object data="{{ '/files/pracheta_poster.pdf' | relative_url }}" type="application/pdf" width="100%" height="600">
  <p>Unable to display the poster preview. <a href="{{ '/files/pracheta_poster.pdf' | relative_url }}">View the poster PDF</a>.</p>
</object>

## Key Methodologies & Toolkit

* **Scientific Computing & ML:** PyTorch, Cantera, NumPy, SciPy
* **CFD Automation:** ANSYS Fluent, PyFluent API
* **Physical Domain and Concepts:** Reacting Flows, Chemical Kinetics, Laminar Flame Speed, Convective Heat Transfer
