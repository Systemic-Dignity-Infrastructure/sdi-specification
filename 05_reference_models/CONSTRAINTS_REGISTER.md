# Constraints Register

This register separates hard constraints from assumptions. Constraints are externally imposed boundaries that the architecture must operate within. They cannot be changed by the project; they must be designed around.

---

| ID | Constraint | Category | Source | Impact on Design | Mitigation |
|:---|:-----------|:---------|:-------|:-----------------|:-----------|
| C-01 | Institution for Mental Diseases (IMD) exclusion | Federal | 42 CFR §435.1010; Medicaid statute | Facilities with > 16 beds providing psychiatric treatment cannot bill Medicaid | Tower design must classify as residential supportive housing, not psychiatric facility; clinical services delivered via external managed care contracts |
| C-02 | CalAIM billing requires active managed care plan enrollment | State | DHCS CalAIM waiver terms | Residents must be enrolled in a Medi-Cal managed care plan to generate ECM/ILOS revenue | Intake process must include Medi-Cal enrollment verification; Pod Stewards trained as enrollment navigators |
| C-03 | AB 2011 by-right authorization requires prevailing wage | State | California AB 2011, amended by AB 2243 | All construction workers must receive prevailing wage; healthcare benefits required for ≥ 50 units | Construction budget must include prevailing wage premium; apprenticeship program participation required |
| C-04 | LPS Act (WIC §5150/§5350) governs involuntary hold authority | State | California Welfare and Institutions Code | Compelled care requires documented grave disability or imminent danger; 72-hour hold limit (§5150); conservatorship requires court petition (§5350) | Four-condition conjunctive threshold; independent neuropsychiatric evaluation; mandatory 3 voluntary offer cycles |
| C-05 | ADA compliance for all residential units | Federal | Americans with Disabilities Act | All units must meet accessibility standards; reasonable accommodations required | STC 65 acoustic parameter positioned as ADA reasonable accommodation for PTSD sensory processing |
| C-06 | California seismic code for commercial conversion | State | California Building Code | Structural retrofit required for residential occupancy classification | Seismic assessment included in site feasibility; retrofit cost factored into conversion budget |
| C-07 | Fire suppression and egress requirements | State/Local | California Fire Code | Residential occupancy requires upgraded fire suppression, emergency lighting, and egress paths | Fire suppression upgrade included in conversion scope; ground floor commons designed for dual egress |
| C-08 | CEQA environmental review (unless exempt) | State | California Environmental Quality Act | Discretionary projects require environmental impact review | AB 2011 provides statutory CEQA exemption for qualifying by-right projects |
| C-09 | Local zoning for commercial-to-residential conversion | Local | Municipal zoning code | Conversion requires site zoned for office, retail, or parking as principally permitted use | Site selection limited to qualifying zones; AB 2011 overrides local discretionary review |
| C-10 | Federal waiver renewal cycle (Section 1115) | Federal | CMS waiver schedule | CalAIM waiver scheduled for renewal December 2026; continuity of fiscal model depends on renewal | Monitor renewal process; develop contingency fiscal model for post-waiver scenario |
| C-11 | Fair Housing Act compliance | Federal | 42 U.S.C. §§3601–3619 | Cannot discriminate in resident selection on protected characteristics | Intake criteria based exclusively on clinical acuity and sequential priority; documented compliance protocol |
