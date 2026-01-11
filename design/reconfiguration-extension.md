# Reconfiguration Extension

The reconfiguration model extends the baseline configuration problem by introducing:

- Legacy configurations
- Item length constraints
- Cabinet size differentiation
- Cost-based optimization

Unlike pure configuration, reconfiguration allows **reuse, removal, or creation** of entities.

---

## Legacy Configuration

A legacy configuration defines:

- Existing rooms and cabinets
- Existing assignments
- Initial cabinet sizes

The solver may reuse or discard legacy elements based on cost.

---

## Long Items and Cabinet Sizes

- Long items must be placed in **high cabinets**
- High cabinets occupy more room capacity
- Existing cabinets can be resized at a cost

---

## Cost-Based Optimization

Each change has an associated cost, including:

- Creating new cabinets or rooms
- Removing legacy elements
- Changing cabinet sizes
- Modifying assignments

The solver minimizes total reconfiguration cost while restoring consistency.
