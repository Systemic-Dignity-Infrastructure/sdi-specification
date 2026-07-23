# Systemic Dignity Infrastructure

**An open engineering specification for reversing chronic unsheltered homelessness.**

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

---

## What Is This?

This repository is the reference specification for the **Systemic Dignity Infrastructure (SDI)** — a three-layer, sequentially dependent architecture that treats chronic homelessness as a systems engineering failure rather than a resource deficiency.

The framework integrates:

1. **Material Dignity Infrastructure (MDI)** — Physical stabilization via surplus real estate conversion
2. **Relational Dignity Infrastructure (RDI)** — Social architecture via Dunbar-scale cohorts and Pod Stewards
3. **Economic Dignity Infrastructure (EDI)** — Cooperative micro-economies bridging the Return Deficit to market tenancy

> **Start here:** Read the [Executive Summary](00_executive_summary/EXECUTIVE_SUMMARY.md) for a complete overview in under ten minutes.

---

## Repository Structure

```
sdi-specification/
├── 00_executive_summary/    Executive Summary and onboarding
├── 01_vision/               The Uncompromising Engineering Standard
├── 02_architecture/         System Context and Repository Architecture diagrams
├── 03_specifications/       Municipal Pilot Specifications (gating criteria)
├── 04_working_papers/       The five-paper theoretical arc (LaTeX + PDF)
│   ├── wp1_stewardship_model/
│   ├── wp2_surplus_capacity/
│   ├── wp3_los_angeles_pipeline/
│   ├── wp4_human_layer/
│   └── wp5_economic_dignity/
├── 05_reference_models/     Assumptions, Constraints, and Risk Registers
├── 06_verification/         Requirements Traceability and Verification Matrices
├── 07_governance/           Project governance and split-authority protocol
├── 08_contribution_guide/   Contributor onboarding and domain-specific tasks
├── 09_glossary/             Systemic Dignity Glossary and Concept Index
├── templates/               Shared LaTeX preamble and metadata
├── Makefile                 Automated paper compilation system
├── CITATION.cff             Machine-readable citation metadata
└── LICENSE                  CC BY-SA 4.0
```

---

## Quick Navigation

| I want to... | Go to... |
|:-------------|:---------|
| Understand the architecture in 10 minutes | [Executive Summary](00_executive_summary/EXECUTIVE_SUMMARY.md) |
| See the system flow diagram | [Architecture Diagrams](02_architecture/ARCHITECTURE_DIAGRAMS.md) |
| Read the theoretical papers | [Working Papers](04_working_papers/) |
| Understand a specific term | [Glossary](09_glossary/Systemic_Dignity_Glossary.md) |
| Find where a concept is defined | [Concept Index](09_glossary/CONCEPT_INDEX.md) |
| Evaluate pilot feasibility | [Pilot Specifications](03_specifications/PILOT-SPECIFICATIONS.md) |
| Audit engineering claims | [Verification Matrix](06_verification/VERIFICATION_MATRIX.md) |
| Review assumptions and risks | [Reference Models](05_reference_models/) |
| Contribute to the project | [Contribution Guide](08_contribution_guide/CONTRIBUTING.md) |
| Cite this work | [CITATION.cff](CITATION.cff) |

---

## Building the Papers

The working papers are authored in LaTeX. To compile locally:

```bash
make all      # Build all five papers
make wp1      # Build WP1 only
make clean    # Remove build artifacts
make verify   # Check citation key resolution
```

---

## Contributing

This is an open-source engineering project. We actively seek contributions from:

- Systems engineers and data scientists
- Econometricians and financial modelers
- Urban planners and real estate analysts
- Clinical directors and social work researchers
- Municipal administrators and Medicaid waiver architects
- Legal scholars specializing in housing and civil liberties

See the [Contribution Guide](08_contribution_guide/CONTRIBUTING.md) for domain-specific entry points.

---

## License

This project is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](LICENSE).
