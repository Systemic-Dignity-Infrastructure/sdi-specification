# Project Governance: Systemic Dignity Infrastructure (SDI)

This document covers two different things, and keeps them separate: who maintains this repository, and how the housing model it specifies is meant to be governed if anyone actually builds it.

## Who Maintains This Repository

This is an independent, single-author project. There is no organization, no board, no executive director, and no formal institutional structure behind it. The author is Charles J. DiBella, as recorded in `CITATION.cff`, and decisions about what goes into this repository are made directly by that author through ordinary Git commits. There is no separate approval process to describe here.

There is no board, media office, or funding-intake apparatus to route inquiries through, and none is being invented for appearance's sake. If the project ever reaches the point of needing one, it will be described here when it actually exists.

The sections below are different. They describe how the housing model itself would need to be governed to work as intended if a municipality or operator built the physical facility (covering resident rights, audit independence, and telemetry consent). That content is retained because it forms part of the engineering specification, not because it describes how this GitHub repository operates.

---

## 1. Cohort Scoping Restriction

The Systemic Dignity Infrastructure is engineered exclusively for the chronic, high-acuity unsheltered population. The mega-tower stabilization architecture is not designed for economically displaced individuals whose primary barrier is rent burden or job loss. That population requires rapid rehousing or rental vouchers. This scope restriction prevents the architecture from being misapplied beyond the evidentiary foundation that supports it.

---

## 2. Intake Sequencing

Housing placement is immediate. The architecture eliminates any mandatory sequential recovery phase prior to granting sovereign tenancy. A resident receives a locked ALMU upon intake processing through the Ground Floor Airlock. All clinical stabilization, psychiatric care, and social service delivery occur in situ behind the locked door. This sequencing aligns the specification with the established Housing First evidence base, which demonstrates that biological stabilization accelerates when the organism possesses unconditional physical security before clinical intervention begins.

---

## 3. Hold Mechanism

The architecture suspends the fundamental right of exit only when an incoming resident lacks cognitive capability due to an acute dual-diagnosis crisis. The system routes these holds exclusively through the jurisdiction's applicable short-term emergency hold statute. In California, this is Welfare and Institutions Code Section 5150, which authorizes a seventy-two-hour involuntary psychiatric hold executed exclusively by peace officers or county-designated professionals.

Facility staff possess zero legal authority to initiate or execute a hold. The ALMU door lock is engineered to revert mechanically from a state-mandated clinical hold to voluntary liberty at hour seventy-three. This physical auto-revert enforces the statutory time boundary through hardware, preventing overstay through staff negligence or bad faith.

LPS conservatorship proceedings under WIC Section 5350 represent a separate judicial process outside the scope of the facility hold mechanism. The architecture does not route through conservatorship.

---

## 4. Eviction Protection

The physical lease is permanently severed from clinical or behavioral compliance. A local operator cannot evict a resident for refusing therapeutic intervention or failing a sobriety screen. Eviction requires verified physical assault or kinetic destruction of the capital property. No other behavioral condition qualifies.

---

## 5. Telemetry Informed Consent

The environmental monitoring system collects the minimum data required for physical asset verification and biological occupancy confirmation. Safety-critical monitoring (fire detection, catastrophic water pressure events, and structural vibration anomalies that threaten the capital asset) is a non-negotiable condition of occupancy, comparable to a smoke detector in ordinary rental housing. It is not linked to funding and carries no bearing on tenure.

Occupancy and billing telemetry, which authenticates biological presence to release Medicaid/CalAIM capital for a given unit, operates behind a strict Zero-Knowledge Billing Firewall and is not a condition of housing. A resident who declines billing-linked monitoring is housed instead through the Philanthropic Set-Aside defined in `10_capital_architecture`: a per-tower allocation of units funded independently of Medicaid billing and reserved for residents who decline occupancy telemetry. Declining billing telemetry means declining that specific funding mechanism, not declining housing.

An independent civil liberties auditor signs off on all data collection protocols prior to any deployment, including the required size and funding source of the Philanthropic Set-Aside. This auditor determines what constitutes safety-critical monitoring. The review evaluates whether each data stream serves a verified engineering purpose or functions as surveillance beyond the stated mandate.

---

## 6. Data Ephemerality

The system mandates twenty-four-hour cryptographic destruction of all raw biological telemetry and environmental sensor data. The architecture refuses to construct historical data lakes mapping individual behavioral patterns. Public transparency dashboards aggregate data at the facility level. The dashboards inject temporal latency by batching occupancy updates. This differential privacy degradation destroys the high-fidelity chronology required to map individual biological patterns. An adversarial actor cannot seize a database that does not exist and cannot scrape a timeline that is intentionally degraded.

---

## 7. Decentralized Ownership

The physical real estate remains legally severed from the global software team through localized community land trusts. A commercial entity retains ownership of the base superstructure to preserve capital efficiency. The residential ALMUs are severed via ninety-nine-year irrevocable master leases held by the localized trusts.

The architecture mandates a Hostile Governance Trust. The trust board is legally prohibited from seating members with financial ties to the capital provider. The board comprises graduated residents and municipal public defenders. A temporal paradox exists before the initial pilot activates. The board must select the auditors before the pilot launches, but graduated residents do not exist until after the pilot succeeds. The architecture resolves this paradox by mandating an interim board clause. Prior to the successful execution of the Singular Prototype, an interim board must be seated. This interim board comprises formerly unsheltered individuals recruited from other established recovery programs alongside municipal public defenders. These interim members execute the initial auditor selection. They serve strictly until true graduated residents exist to replace them. The centralized corporation owns the concrete. The decentralized trust owns the right of occupancy. This severs authoritarian control over the human footprint while preserving the scalability of the mega-tower.

### CLT Board Accountability
Board members serve fixed terms of four years with a maximum of two consecutive terms. A recall mechanism allows a two-thirds vote of the resident council to remove a board member before term expiration. All board members must file annual conflict-of-interest disclosures. These disclosures are published in the public audit record alongside the four external audit outcomes.

---

## 8. Pre-Activation Gates

No site activates until all four independent reviews pass. No capital figure is used in fundraising materials until the independent financial review is complete.

### A. Jurisdiction Attorney Sign-Off
A binding legal verification confirms that the local emergency hold statute aligns with the seventy-two-hour stabilization mechanism. The attorney verifies that facility staff possess zero hold authority under local law. This review must complete before any site activation in a new jurisdiction.

### B. Independent Financial Review
An independent financial reviewer with no stake in the project verifies the fiscal methodology. The review must explicitly validate that the Singular Prototype achieves the **42–52% fully loaded cost arbitrage bound ($24k–$29k)** against the $50k municipal baseline. The review confirms that the baseline municipal avoided cost cites a published source, specifies cost variance across chronic, transitional, and document-isolated populations, quantifies the worst-case friction variable as an explicit mathematical input, and mathematically includes the amortized debt of the $36.9M construction cost in the per-resident figure.

The financial review must include a specialist in California Medi-Cal billing and CalAIM program compliance. This specialist independently audits the Enhanced Care Management and Community Supports revenue offset model. The audit confirms that only roles qualifying under ECM service definitions or ILOS Community Supports categories are included in CalAIM billing projections. Non-clinical operating staff including security, kitchen, facilities, and building maintenance are excluded from any Medicaid revenue offset. The specialist applies per-member-per-month risk adjustment factors reflecting actual Medi-Cal enrollment rates among the target population and the absence of binding statewide ECM/ILOS rate schedules. No CalAIM revenue figure is used in fundraising materials or efficiency surplus projections until this specialist review is complete.

### C. Independent Citation Verification
An external reviewer verifies that every cited source in the working papers exists and states what it is cited as stating. This review goes beyond internal LaTeX key consistency. It confirms the factual accuracy of each citation against the original published text, with direct application to Working Paper Three and Working Paper Five.

### D. Independent Civil Liberties Review
An independent civil liberties auditor reviews all telemetry data collection protocols. The auditor determines the boundary between safety-critical monitoring and surveillance. This review must complete before any telemetry system activates.

---

## 9. Auditor Independence and Selection

Neither the author of this specification nor any operator deploying it may select or compensate any of the four independent reviewers. The Community Land Trust board holds exclusive authority to appoint the financial auditor, the citation verifier, the jurisdiction attorney, and the civil liberties auditor.

The board selects reviewers exclusively from external referral panels provided by academic ethics centers, state bar associations, or recognized disability rights organizations. This selection mechanism eliminates intentional selection bias and prevents the procurement of predictable conclusions.

---

## 10. Public Disclosure of Audit Outcomes

All four external audit outcomes are published in full in this repository. Partial approvals, qualified findings, and complete failures are published in their entirety. The architecture prohibits concealing negative evaluations behind binary pass or fail gate statuses. The public and the residents maintain continuous visibility into the structural health of the system.

---

## 11. Pilot Validation Requirement

A single, independently evaluated Singular Prototype is mandatory before any network-scale multi-tower deployment proceeds. The prototype adopts the **$36.9M**, three-pod tower configuration, comprising 348 residents, 76 permanent staff, and 185,000 gross square feet, as specified in `10_capital_architecture/README.md` and WP6. Three pods is the minimum scale at which the multi-pod fixed-cost amortization the architecture depends on can be observed and measured. The prototype focuses on adaptive-reuse conversion and voluntary stabilization, and operates in partnership with an existing local operator possessing established clinical and residential capacity. An independent third-party evaluator measures outcomes at ninety, one hundred eighty, and three hundred sixty-five days. The **Seven Binary Verification Metrics** constituting the Singular Prototype Threshold must pass; failure to clear these thresholds at 365 days triggers a mechanical refusal to deploy (a hard stop), permanently halting network expansion until the architecture is mathematically corrected.

---

## 12. Periodic Re-Review

The governance framework mandates a triennial evidence review. Every thirty-six months, the entire architectural specification undergoes evaluation against updated Housing First outcomes and contemporary peer-reviewed homelessness intervention evidence. An external review panel, appointed through the same CLT board selection mechanism governing the four pre-activation auditors, conducts this evaluation. The review determines whether the specification's falsifiable claims remain supported by current empirical data. If the evidence base has shifted, the specification is revised to match. This cycle guarantees that the architecture remains empirically falsifiable on a continuous basis.

---

## 13. Amendments to This Document

This document can be revised like any other file in the repository, through ordinary commits. Changes to the operational sections above (1 through 12) should be made deliberately. Those sections describe safeguards (resident eviction protection, telemetry consent, and auditor independence) that the rest of the specification depends on. A change that weakens one of them must state so plainly in the commit message.
