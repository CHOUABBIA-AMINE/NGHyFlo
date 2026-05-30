# Reference Repository Inventory

## Workspace inventory

Date of inventory: 2026-05-30.

| Repository | Expected path | Availability in current workspace | Notes |
| --- | --- | --- | --- |
| HyFloAPI | `/workspace/HyFloAPI` | Not available | Required before domain extraction, workflow cataloging, and business rule analysis can be completed. |
| NGHyFloAPI | `/workspace/NGHyFloAPI` | Not available | Required before architecture lessons, documentation lessons, standards, audit findings, and implementation cautions can be analyzed. |
| NGHyFlo | `/workspace/NGHyFlo` | Available | Target repository. Documentation baseline has been created here. |

## Consequence of missing references

Because HyFloAPI and NGHyFloAPI are unavailable in the current workspace, the NGHyFlo repository must not yet contain:

- Generated target implementation code.
- Final target architecture decisions.
- Final engineering standards derived from the reference systems.
- Product or implementation roadmaps that claim reference-backed prioritization.
- Domain models that claim completeness.

## Required next inventory action

Provide read-only access to HyFloAPI and NGHyFloAPI beside NGHyFlo, preferably as sibling directories under `/workspace`, then rerun the reference analysis protocol.
