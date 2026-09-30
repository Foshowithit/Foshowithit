# Adam Normandin

I build AI agent infrastructure.

My main work is **RCOS — Recursive Capability Operating System**: a system for routing goals into durable execution, verifying results with evidence, and reusing capabilities that pass explicit evaluation.

## RCOS

`goal → workflow manager → execution → evidence → evaluation → reusable capability`

Current focus:
- durable agent execution and recovery
- capability acquisition, evaluation, promotion, and reuse
- evidence-backed receipts instead of self-reported success
- DSH / Archon integration
- operator tooling for inspecting and controlling agent work

The goal is simple: make agent systems more capable without making their behavior less inspectable.
