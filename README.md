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

## Visual Results

Representative solver outputs are provided in the `visuals/` directory, including:

- Basic house configuration
- Reconfiguration from legacy state
- Long-item constraints
- Cabinet resizing
- New room creation
- Empty starting configuration

Each visual corresponds to a specific problem instance discussed in the evaluation.

---

## Academic Context

This project was completed as part of graduate-level coursework on **knowledge representation and reasoning**, based on established formulations of the House (Re-)Configuration Problem from prior research.

All figures and problem descriptions are used with academic attribution.

---
