# Ansys_Discrete_Particle_Modeling
CFD-DPM simulation of particle-laden compressible flow through a 2D converging-diverging nozzle using ANSYS Fluent.

# Discrete Phase Modeling of Particle Flow Through a Converging-Diverging Nozzle

## Overview

This project presents a **Discrete Phase Model (DPM)** simulation of particle-laden flow through a two-dimensional converging-diverging (CD) nozzle using **ANSYS Fluent**.

The simulation investigates the motion and behavior of discrete particles as they are transported through the nozzle by the continuous gas phase. Particle trajectories, velocity, residence time, and particle behavior across the converging section, throat, and diverging section were analyzed.

---

## Objectives

* Model compressible gas flow through a converging-diverging nozzle.
* Introduce a discrete particle phase into the continuous flow.
* Study particle trajectories through the nozzle.
* Analyze particle velocity and motion in different sections of the nozzle.
* Investigate the interaction between the continuous fluid phase and discrete particles.
* Visualize particle behavior using ANSYS Fluent post-processing tools.

---

## Software Used

* **ANSYS Workbench**
* **ANSYS Fluent**
* **ANSYS SpaceClaim**
* **ANSYS Meshing**

---

## Geometry

A **2D converging-diverging nozzle** was modeled for the simulation.

### Geometry Parameters

| Parameter                 |        Value |
| ------------------------- | -----------: |
| Inlet height              |       100 mm |
| Throat height             |   28.7706 mm |
| Outlet height             | 172.3349  mm |
| Nozzle length             |    254.46 mm |
| Converging section length |  88.7366  mm |
| Diverging section length  | 165.4602  mm |

### Nozzle Geometry

---

## Mesh

The nozzle geometry was discretized using a **___ mesh**.

### Mesh Information

| Parameter                  | Value |
| -------------------------- | ----: |
| Number of elements         |   ___ |
| Number of nodes            |   ___ |
| Minimum orthogonal quality |   ___ |
| Maximum skewness           |   ___ |
| Mesh type                  |   ___ |

### Computational Mesh

---

# Continuous Phase Setup

The continuous phase consists of **___** flowing through the nozzle.

### Solver Settings

| Parameter                  | Setting      |
| -------------------------- | ------------ |
| Solver                     | ___          |
| Flow                       | Compressible |
| Fluid                      | Air          |
| Energy equation            | ___          |
| Viscous model              | SST k-omega  |
| Density model              | ___          |
| Pressure-velocity coupling | ___          |
| Solution method            | ___          |

### Operating Conditions

| Parameter              |      Value |
| ---------------------- | ---------: |
| Inlet pressure         | 1800000 Pa |
| Inlet temperature      |      ___ K |
| Outlet pressure        |     ___ Pa |
| Operating pressure     |     ___ Pa |
| Specific heat ratio, γ |        ___ |

---

# Discrete Phase Setup

The **Discrete Phase Model (DPM)** was enabled to simulate the motion of particles within the continuous gas flow.

### Particle Properties

| Parameter                  |                    Value |
| -------------------------- | -----------------------: |
| Particle material          |             Water-liquid |
| Particle density           |                    kg/m³ |
| Particle diameter          |                  0.01 mm |
| Particle shape             |                          |
| Particle mass flow rate    | 1 x 10^-8  -  1 x 10^-20 |
| Number of particle streams |                      500 |

### DPM Settings

| Parameter                    | Setting  |
| ---------------------------- | -------- |
| DPM formulation              | ___      |
| Particle tracking            | Unsteady |
| Continuous phase interaction | Yes      |
| Turbulent dispersion         | ___      |
| Drag law                     | ___      |
| Particle-wall interaction    | ___      |
| Particle escape condition    | ___      |
| Particle trap condition      | ___      |

---

## Particle Injection

Particles were introduced into the flow through the **___** boundary.

### Injection Parameters

| Parameter                    |                    Value |
| ---------------------------- | -----------------------: |
| Injection type               |                      ___ |
| Injection location           |                      ___ |
| Initial particle velocity    |                  ___ m/s |
| Initial particle temperature |                    ___ K |
| Particle diameter            |                 0.01 mm  |
| Particle mass flow rate      | 1 x 10^-8  -  1 x 10^-20 |
| Injection direction          |                      ___ |

---

# Convergence

The continuous-phase solution was iterated for approximately 400** iterations**.

The convergence behavior was monitored using the residuals and relevant flow parameters.

---

# Results

## Continuous Phase

The continuous-phase solution was analyzed before examining the particle trajectories.

### Mach Number Distribution

**Maximum Mach number:** 3.42

**Mach number at throat:** 1.38

### Pressure Distribution

**Maximum pressure:** 1800000 Pa

**Minimum pressure:** 26300 Pa

### Velocity Distribution

**Maximum velocity:** 920 m/s

---

# Discrete Phase Results

## Particle Trajectories

Particle trajectories were generated to visualize the motion of the discrete phase through the converging-diverging nozzle.

The trajectories show how the particles respond to the accelerating and decelerating continuous flow through the nozzle.

---

## Particle Velocity

The particle velocity distribution was analyzed along the nozzle.

**Maximum particle velocity:** 612 m/s

**Minimum particle velocity:**  61.2 m/s

---

## Particle Residence Time

The residence time of particles within the computational domain was analyzed.

**Minimum residence time:** ___ s

**Maximum residence time:** ___ s

---

## Particle Behavior at the Nozzle

The particle behavior was examined at different sections of the nozzle.

| Location           | Particle Velocity | Particle Mach Number | Observation |
| ------------------ | ----------------: | -------------------: | ----------- |
| Inlet              |               ___ |                  ___ | ___         |
| Converging section |               ___ |                  ___ | ___         |
| Throat             |               ___ |                  ___ | ___         |
| Diverging section  |               ___ |                  ___ | ___         |
| Outlet             |               ___ |                  ___ | ___         |

---

# Particle-Flow Interaction

The discrete particles experience forces due to their interaction with the continuous gas phase.

The dominant particle forces considered in this simulation were:

* Drag force
* ---
* ---

The particle trajectories demonstrate the response of the discrete phase to changes in the velocity and pressure fields of the continuous phase.

---

# Observations

Based on the CFD-DPM results:

* The continuous gas phase accelerates through the converging section of the nozzle.
* Particle velocity changes as the particles are transported through the varying-area nozzle.
* The particle trajectories show **___**.
* The particles reach a maximum velocity of approximately **___ m/s**.
* At the throat, the particle behavior is characterized by **___**.
* In the diverging section, the particles **___**.
* Particle-wall interaction resulted in **___**.
* The particle response to the continuous phase was **___**.

---

# Quantitative Results

The following plot shows the variation of **___** along the nozzle.

### Key Results

| Parameter                    |   Value |
| ---------------------------- | ------: |
| Maximum gas velocity         | ___ m/s |
| Maximum particle velocity    | 612 m/s |
| Maximum gas Mach number      |    3.42 |
| Maximum particle Mach number |     ___ |
| Particle residence time      |   ___ s |
| Particle mass flow rate      |     ___ |
| Particle escape fraction     |     ___ |
| Particle trap fraction       |     ___ |

---

# Conclusion

The DPM simulation was used to investigate the behavior of discrete particles transported through a converging-diverging nozzle.

The simulation demonstrated how particle motion is influenced by the changing flow conditions within the nozzle. The particle trajectories and velocity distribution provided insight into the response of the discrete phase as it passed through the converging section, throat, and diverging section.

This project provided practical experience in **ANSYS Fluent, compressible flow simulation, Discrete Phase Modeling, particle injection, particle tracking, CFD post-processing, and interpretation of particle-flow interaction**.

---

# Skills Demonstrated

* Computational Fluid Dynamics (CFD)
* ANSYS Fluent
* Discrete Phase Modeling (DPM)
* Compressible Flow Analysis
* Particle Tracking
* Particle Injection
* Mesh Generation
* Boundary Condition Setup
* CFD Post-Processing
* Flow Visualization
* Particle Trajectory Analysis
* Pressure and Velocity Analysis

---

# Project Information

**Author:** Mohammed Sadman Adib

**Institution:** BUET

**Date:** ___

**ANSYS Version:** 2021 R1

---

