# System Context Diagram

The following diagram illustrates the complete SDI architecture as a sequential pipeline from street homelessness through to independent market tenancy.

```mermaid
flowchart TD
    A["Street Homelessness"] --> B["Phase Zero: Ground Floor Intake Airlock"]
    B --> C["Material Dignity Infrastructure (MDI)"]
    C --> D["Biological Stabilization (≤ 72 hours)"]
    D --> E["Relational Dignity Infrastructure (RDI)"]
    E --> F["Dunbar-Scale Cohorts + Pod Stewards (1:7)"]
    F --> G["Identity Capital Accumulation"]
    G --> H["Economic Dignity Infrastructure (EDI)"]
    H --> I["Cooperative Reintegration Mechanism"]
    I --> J["Return Deficit Bridged"]
    J --> K["Tenancy Bridge Guarantee"]
    K --> L["Independent Market Tenancy"]
    L --> M["Long-Term Stability (24-Month Verification)"]

    style A fill:#8B0000,color:#fff
    style C fill:#1a5276,color:#fff
    style E fill:#1a5276,color:#fff
    style H fill:#1a5276,color:#fff
    style L fill:#196F3D,color:#fff
    style M fill:#196F3D,color:#fff
```

---

# Repository Architecture Diagram

The following diagram illustrates the organizational structure of the `sdi-specification` repository and the relationships between document categories.

```mermaid
flowchart LR
    ROOT["sdi-specification"] --> ES["00 Executive Summary"]
    ROOT --> VIS["01 Vision"]
    ROOT --> ARCH["02 Architecture"]
    ROOT --> SPEC["03 Specifications"]
    ROOT --> WP["04 Working Papers"]
    ROOT --> REF["05 Reference Models"]
    ROOT --> VER["06 Verification"]
    ROOT --> GOV["07 Governance"]
    ROOT --> CONT["08 Contribution Guide"]
    ROOT --> GLOS["09 Glossary"]

    WP --> WP1["WP1: Foundational Theory"]
    WP --> WP2["WP2: Surplus Capacity"]
    WP --> WP3["WP3: LA Pipeline"]
    WP --> WP4["WP4: Human Layer"]
    WP --> WP5["WP5: Economic Dignity"]

    REF --> ASM["Assumptions Register"]
    REF --> CST["Constraints Register"]
    REF --> RSK["Risk Register"]

    VER --> RTM["Requirements Traceability"]
    VER --> VMX["Verification Matrix"]

    GLOS --> GLO["Glossary"]
    GLOS --> CIX["Concept Index"]

    VIS -.->|"defines standard for"| SPEC
    SPEC -.->|"gates"| WP
    WP -.->|"validated by"| VER
    REF -.->|"constrains"| WP

    style ROOT fill:#2C3E50,color:#fff
    style WP fill:#1a5276,color:#fff
    style VER fill:#7D3C98,color:#fff
    style REF fill:#A04000,color:#fff
    style GLOS fill:#1E8449,color:#fff
```
