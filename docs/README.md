# NGHyFlo Documentation Baseline

NGHyFlo is the clean target repository for an enterprise-grade industrial pipeline operations platform for Sonatrach.

This repository is not a technical rewrite of either reference system. It is a strategic evolution that must be grounded in documented analysis of:

- **HyFloAPI**: legacy business and domain reference; mutation is not allowed.
- **NGHyFloAPI**: current next-generation backend, architecture, documentation, standards, generated roadmaps, audit findings, and implementation cautions; mutation is not allowed.
- **NGHyFlo**: clean target implementation repository; mutation is allowed.

## Current repository state

Only the NGHyFlo target repository is present in this workspace. The HyFloAPI and NGHyFloAPI reference repositories are not currently available under `/workspace`, so this baseline intentionally avoids producing implementation code, target architecture, target standards, or a delivery roadmap that would imply completed reference analysis.

## Documentation-first rule

Before NGHyFlo introduces application code or commits to implementation architecture, the project must complete and commit the reference analysis package defined in this documentation set.

Required entry points:

1. [Strategic Rebuild Charter](00-governance/strategic-rebuild-charter.md)
2. [Reference Repository Inventory](01-reference-analysis/reference-repository-inventory.md)
3. [Reference Analysis Protocol](01-reference-analysis/reference-analysis-protocol.md)
4. [Domain Discovery Catalog](02-domain-discovery/domain-discovery-catalog.md)
5. [Documentation-First Delivery Gate](03-delivery-gates/documentation-first-delivery-gate.md)
