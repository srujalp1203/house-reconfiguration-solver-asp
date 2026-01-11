# ASP Modeling Approach

The House (Re-)Configuration Problem is modeled declaratively using **Answer Set Programming (ASP)**, where constraints and optimization objectives are expressed as logical rules rather than procedural code.

The model defines:

- Entities (persons, things, cabinets, rooms)
- Assignment relations
- Capacity and compatibility constraints
- Optimization criteria for reconfiguration

ASP enables concise expression of combinatorial constraints while allowing the solver to explore multiple valid configurations.

---

## Core Modeling Principles

- **Declarative constraints** define what constitutes a valid configuration
- **Separation of concerns** between configuration rules and optimization rules
- **Explicit ownership propagation** to enforce consistency
- **Closed-world assumption** to prevent unintended assignments

---

## Output Interpretation

Solver outputs are interpreted using predicates such as:

- `cabinet/1`, `room/1`
- `cabinetTOthing/2`
- `roomTOcabinet/2`
- `cabinetHigh/1`, `cabinetSmall/1`

Each answer set corresponds to a complete and valid house configuration.

