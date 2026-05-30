# Strategic Rebuild Charter

## Purpose

NGHyFlo exists to create a clean, enterprise-grade, industrial pipeline operations platform for Sonatrach while preserving the strongest business concepts from HyFloAPI and the best architectural lessons from NGHyFloAPI.

## Repository roles

| Repository | Role | Mutation policy |
| --- | --- | --- |
| HyFloAPI | Legacy business/domain reference model and accumulated Sonatrach pipeline operations knowledge. | Read-only |
| NGHyFloAPI | Current next-generation backend reference, documentation reference, architecture lessons, standards, generated roadmaps, audit findings, and implementation cautions. | Read-only |
| NGHyFlo | Clean target repository for the new platform. | Mutable |

## Non-goals

NGHyFlo must not be treated as:

- A refactor of HyFloAPI.
- A refactor of NGHyFloAPI.
- A copy of either implementation.
- A code-first rewrite that loses accumulated operational knowledge.

## Strategic principles

1. **Domain preservation before implementation**: business concepts must be captured and reviewed before application code is introduced.
2. **Architecture lessons before architecture decisions**: target architecture decisions must cite lessons, risks, and cautions found in NGHyFloAPI.
3. **Clean implementation boundary**: source code must be newly authored in NGHyFlo unless a later legal and technical review explicitly approves reuse.
4. **Traceability**: every major feature, module, architecture decision, and operational workflow should trace back to documented reference analysis or an explicit new requirement.
5. **Industrial reliability**: the platform must be designed for pipeline operations where correctness, auditability, observability, security, and maintainability matter more than short-term delivery speed.

## Initial constraint

The current workspace contains only NGHyFlo. HyFloAPI and NGHyFloAPI are not available for direct analysis in this environment. Until those repositories are made available, this repository should contain only documentation scaffolding, analysis protocols, and readiness gates.
