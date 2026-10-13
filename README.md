# CFD Simulation of Incompressible Flow in a 90° Bend

## Project Overview

This project investigates two-dimensional, steady, viscous, incompressible flow through a 90° bend using Computational Fluid Dynamics (CFD). The fluid is assumed to have constant density, with flow entering through the left boundary and exiting through the lower-right boundary. All other boundaries are treated as impermeable walls.

The governing flow equations are solved numerically using an artificial compressibility, pressure-correction, or projection method to couple the velocity and pressure fields.

## Problem Description

The simulation examines the effects of Reynolds number and geometric configuration on the flow field inside the bend.

### Simulation Parameters

* **Reynolds number (Re):** 10, 100, and 500.
* **Geometry ratio (H/L):** 0.5, 1, and 2.
* **Fluid model:** Viscous, incompressible fluid with constant density.
* **Boundary conditions:** Inlet on the left, outlet at the lower-right boundary, and impermeable walls along the remaining boundaries.

The Reynolds number is varied by adjusting the fluid viscosity while maintaining the other relevant flow conditions.

## Numerical Method

A numerical method for incompressible flow is implemented to obtain the velocity and pressure fields. The selected approach is used to enforce mass conservation and satisfy the incompressibility constraint.

## Objectives

* Investigate the influence of Reynolds number on the flow field in a 90° bend.
* Examine the effects of the geometric ratio \(H/L\) on the velocity distribution.
* Study flow behaviour at low and moderate Reynolds numbers.
* Implement a numerical method for solving the incompressible Navier–Stokes equations.
* Compare flow fields across different Reynolds numbers and geometric configurations.

## Expected Outputs

Depending on the implemented solver, the results may include:

* Velocity contours and vector fields.
* Pressure distribution.
* Streamlines and recirculation regions.
* Comparisons between different Reynolds numbers and geometry ratios.
