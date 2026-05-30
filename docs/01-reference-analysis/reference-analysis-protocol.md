# Reference Analysis Protocol

This protocol defines the analysis that must happen before NGHyFlo produces implementation code, final target architecture, engineering standards, or a delivery roadmap.

## Analysis inputs

The analysis must use the repositories according to their roles:

- HyFloAPI is the business/domain reference.
- NGHyFloAPI is the architecture, documentation, lessons, standards, roadmap, audit, and caution reference.
- NGHyFlo is the clean target repository where findings are documented and future implementation occurs.

## HyFloAPI analysis outputs

The HyFloAPI review must produce documented outputs for:

1. Business capabilities and bounded contexts.
2. Operational workflows for pipeline monitoring and operations.
3. Domain entities, aggregates, value objects, and relationships.
4. Business rules, calculations, validations, and thresholds.
5. Role, permission, approval, and accountability concepts.
6. External integrations and data exchange patterns.
7. Reporting, audit, history, and traceability requirements.
8. Operational terminology that must be preserved or clarified.
9. Known pain points, implicit coupling, and legacy constraints that must not be blindly carried forward.

## NGHyFloAPI analysis outputs

The NGHyFloAPI review must produce documented outputs for:

1. Architecture decisions and their outcomes.
2. Documentation patterns worth preserving.
3. Engineering standards worth adopting, revising, or rejecting.
4. Generated roadmaps and whether they remain valid.
5. Audit findings and remediation status.
6. Implementation cautions and anti-patterns.
7. Security, observability, testing, and deployment lessons.
8. Data modeling and API design lessons.
9. Known gaps between intended architecture and actual implementation.

## Traceability requirements

Each extracted finding should include:

- Source repository.
- Source file path.
- Source line range where practical.
- Finding type: domain, workflow, rule, architecture lesson, risk, caution, standard, or open question.
- Confidence level.
- Recommendation for NGHyFlo.

## Prohibited shortcuts

The analysis must not:

- Copy implementation code from either reference repository into NGHyFlo.
- Treat file names or module names as sufficient evidence of domain boundaries.
- Convert legacy technical structure directly into the target architecture.
- Produce a roadmap before unresolved domain and architecture questions are documented.
- Collapse business requirements into framework-specific implementation tasks.
