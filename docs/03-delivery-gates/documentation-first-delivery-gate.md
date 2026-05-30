# Documentation-First Delivery Gate

This gate prevents NGHyFlo from becoming a code-first rewrite before the reference repositories have been analyzed.

## Gate status

Current status: **closed**.

Reason: HyFloAPI and NGHyFloAPI are not available in the current workspace, and the required reference analysis package has not been completed.

## Entry criteria for implementation work

Implementation work may begin only after the following artifacts exist in NGHyFlo:

- Completed reference repository inventory.
- HyFloAPI domain analysis.
- NGHyFloAPI architecture and lessons analysis.
- Domain discovery catalog with traceable source evidence.
- Open-question register with ownership and resolution status.
- Initial target architecture proposal that cites reference analysis findings.
- Engineering standards proposal that cites NGHyFloAPI lessons and current enterprise needs.
- Risk register covering migration, data integrity, operational continuity, security, and maintainability.

## Allowed work while the gate is closed

The following work is allowed:

- Documentation scaffolding.
- Reference analysis templates.
- Repository governance documents.
- Decision-record templates.
- Read-only investigation of HyFloAPI and NGHyFloAPI after they become available.

## Blocked work while the gate is closed

The following work is blocked:

- Application source code.
- Database schema design.
- API contracts.
- Final architecture decisions.
- Final engineering standards.
- Delivery roadmaps that imply implementation sequencing.

## Exit criteria

The gate may be opened only when the required artifacts have been reviewed and committed, and when each target architecture or delivery decision can be traced to documented evidence or an explicit stakeholder decision.
