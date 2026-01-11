# Solver Strategy

The solver follows a two-stage strategy:

1. **Constraint Satisfaction**
   - Generate all valid configurations
   - Enforce ownership, capacity, and compatibility rules

2. **Optimization**
   - Apply weighted cost functions
   - Identify minimum-cost configurations

---

## Optimization Behavior

- Multiple optimal answer sets may exist
- Cost weights influence reuse vs. replacement decisions
- Larger instances increase grounding and solving time

Solver performance varies significantly with constraint density and problem size.

