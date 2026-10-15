# Systemic Dignity Infrastructure

**An engineering specification for reversing chronic unsheltered homelessness, written by someone who lived it.**

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

---

## Why This Exists

I lived outdoors nomadically between 1994 and 2024. This specification turns thirty years of direct knowledge regarding chronic homelessness into concrete engineering proposals. It provides specific numbers, floor plans, and failure modes rather than abstract policy philosophies.

This project is not the product of an institution, nonprofit, or university center. It represents an independent working theory developed over three decades and refined through collaboration with artificial intelligence systems to structure technical data. Certain sections remain more polished than others as active revisions proceed.

Read more about the background in [AUTHOR.md](AUTHOR.md).

---

## What is in This Repository

This repository contains the reference specification for the **Systemic Dignity Infrastructure (SDI)**. It models chronic homelessness as a systems engineering failure across three sequentially dependent layers. Each layer establishes the biological, relational, or economic foundation required for long-term stability.

The architecture is anchored in a concrete reference design called the **Singular Prototype**. This facility requires a $36.9M capital investment across a three-pod, 348-resident adaptive-reuse building. It validates biological stabilization at minimum viable scale before multi-tower expansion.

The specification integrates three layers:

1. **Material Dignity Infrastructure (MDI)**: Physical stabilization via surplus real estate conversion.
2. **Relational Dignity Infrastructure (RDI)**: Social architecture using Dunbar-scale cohorts and live-in Pod Stewards.
3. **Economic Dignity Infrastructure (EDI)**: Cooperative micro-economies bridging the Return Deficit back to independent tenancy.

> **Start here:** The [Executive Summary](00_executive_summary/EXECUTIVE_SUMMARY.md) provides a complete overview in under ten minutes.

---

## Repository Structure

```
sdi-specification/
├── 00_executive_summary/    Executive Summary and onboarding
├── 01_vision/               The Uncompromising Engineering Standard
├── 02_architecture/         System Context and Repository Architecture diagrams
├── 03_specifications/       Municipal Pilot Specifications (gating criteria)
├── 04_working_papers/       Six working papers (LaTeX + Markdown) developing the theory
│   ├── wp1_stewardship_model/
│   ├── wp2_surplus_capacity/
│   ├── wp3_los_angeles_pipeline/
│   ├── wp4_human_layer/
│   ├── wp5_economic_dignity/
│   └── wp6_singular_prototype/
├── 05_reference_models/     Assumptions, constraints, and the risk register
├── 06_verification/         Requirements traceability and verification matrices
├── 07_governance/           How the housing model (not this repo) is meant to be governed
├── 08_contribution_guide/   Contributor onboarding and domain-specific tasks
├── 09_glossary/             Systemic Dignity glossary and concept index
├── 10_capital_architecture/ Capital structure and financing pipeline
├── 11_policy_analysis/      External policy evaluations and comparative case studies
├── templates/               Shared LaTeX preamble and metadata
├── Makefile                 Automated paper compilation system
├── AUTHOR.md                Who wrote this, and why
├── CITATION.cff              Machine-readable citation metadata
└── LICENSE                   CC BY-SA 4.0
```

---

## Quick Navigation

| I want to... | Go to... |
|:-------------|:---------|
| Understand the architecture in 10 minutes | [Executive Summary](00_executive_summary/EXECUTIVE_SUMMARY.md) |
| See the system flow diagram | [Architecture Diagrams](02_architecture/ARCHITECTURE_DIAGRAMS.md) |
| Read the working papers | [Working Papers](04_working_papers/) |
| Understand a specific term | [Glossary](09_glossary/Systemic_Dignity_Glossary.md) |
| Find where a concept is defined | [Concept Index](09_glossary/CONCEPT_INDEX.md) |
| Evaluate pilot feasibility | [Pilot Specifications](03_specifications/PILOT-SPECIFICATIONS.md) |
| Audit engineering claims | [Verification Matrix](06_verification/VERIFICATION_MATRIX.md) |
| Review assumptions and risks | [Reference Models](05_reference_models/) |
| Understand the capital structure | [Capital Architecture](10_capital_architecture/) |
| Read comparative policy analyses | [Policy Analysis](11_policy_analysis/) |
| Contribute to the project | [Contribution Guide](08_contribution_guide/CONTRIBUTING.md) |
| Cite this work | [CITATION.cff](CITATION.cff) |

---

## Status

This repository is an active engineering specification rather than a finished, peer-reviewed academic publication. Working Papers 1 through 4 are complete drafts. Working Papers 5 and 6 remain in active development. Independent review gates defined in [GOVERNANCE.md](07_governance/GOVERNANCE.md) and [06_verification/](06_verification/) establish the formal verification criteria required prior to physical deployment. All financial and operational figures represent baseline hypotheses subject to external audit.

---

## Building the Papers

The working papers are authored in LaTeX. To compile locally:

```bash
make all      # Build all working papers
make wp1      # Build WP1 only
make clean    # Remove build artifacts
make verify   # Check citation key resolution
```

---

## Contributing

This is an open project. Contributions are welcome from:

- Systems engineers and data scientists
- Econometricians and financial modelers
- Urban planners and real estate analysts
- Clinical directors and social work researchers
- Municipal administrators and Medicaid waiver specialists
- Legal scholars specializing in housing and civil liberties

See the [Contribution Guide](08_contribution_guide/CONTRIBUTING.md) for domain-specific entry points.

---

## License & Attribution

This project is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](LICENSE). See [CITATION.cff](CITATION.cff) for citation metadata.

## Author

Charles J. DiBella. See [AUTHOR.md](AUTHOR.md).

