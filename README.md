# House (Re-)Configuration Solver using Answer Set Programming (ASP)

This repository documents the modeling, design, and evaluation of a solver for the **House (Re-)Configuration Problem (HCP/HRP)** using **Answer Set Programming (ASP)** and **Clingo**.

The project focuses on encoding complex spatial, ownership, and capacity constraints, and extending a baseline configuration model to support **cost-based reconfiguration optimization**.

> **Note**  
> This repository contains documentation, solver outputs, and visual artifacts only.  
> Source code and executable ASP encodings are intentionally omitted to comply with academic integrity policies.

---

## Problem Overview

The House (Re-)Configuration Problem models the task of assigning **things** to **cabinets** and **cabinets** to **rooms** under strict constraints:

- Ownership consistency
- Capacity limits
- Spatial constraints
- Compatibility between long items and cabinet sizes

The problem exists in two forms:

- **House Configuration Problem (HCP)** — starting from an empty configuration
- **House Reconfiguration Problem (HRP)** — modifying an existing configuration while minimizing change cost

---

## What This Project Demonstrates

- Constraint modeling using Answer Set Programming
- Declarative encoding of ownership, capacity, and compatibility rules
- Optimization using weighted cost functions
- Reconfiguration reasoning with legacy configurations
- Empirical evaluation of solver behavior and scalability

---

## Repository Structure

