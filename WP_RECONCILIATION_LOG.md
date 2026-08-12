# WP Reconciliation Log

Cross-session memory file for the WP1–WP5 reconciliation and hardening protocol. Each session reads its own section and relevant prior sections only.

---

## WP5: Economic Dignity Infrastructure (SSRN 7177118)

### Session A: Substance (Claude Opus 4.6)

#### Stage 0 Numeric Findings
WP5 was **clean** on all seven superseded metric sweeps. No instances of `$36.6M`, `17 FTE`, `612 FTE`, `74%`, `55%`, or unadjusted `$18,000`/`$50,000` comparisons. No AB 2011 citations present (correct — WP5 does not address real estate acquisition).

#### CalAIM / Medicaid Room-and-Board Exclusion Analysis

**The core question:** Does the Tenancy Bridge Guarantee's revenue model survive the federal Medicaid room-and-board exclusion (Social Security Act §1905(a); 42 CFR Part 441)?

**WP5's claim (Line 136):** "While federal Medicaid funding frequently prohibits direct room and board payments the clinical revenue produced by housing navigation and care management services underwrites the administrative overhead required to secure and guarantee external market-rate master leases."

**Verdict: The claim is structurally sound but requires a precision tightening.**

The paper correctly identifies the regulatory constraint and correctly routes around it. The architecture does NOT propose using Medicaid dollars to pay rent. It proposes using CalAIM Community Supports revenue (Housing Transition Navigation Services, Housing Tenancy and Sustaining Services, Enhanced Care Management) to fund the *administrative apparatus* that secures external leases. The actual lease payments come from philanthropic/venture capital (the $36.9M CapEx layer documented in CAPITAL.md and WP1).

**However, three issues require editorial attention:**

1. **"Frequently prohibits" understates the constraint.** The room-and-board exclusion is not a frequent prohibition — it is a categorical federal prohibition under §1905(a). The word "frequently" introduces a false hedge suggesting jurisdictional variation where none exists at the federal level. The variation is in *which services* states have authorized around the exclusion, not in whether the exclusion applies.

2. **Missing: Transitional Rent Community Support.** Since the paper was drafted, DHCS has introduced "Transitional Rent" as a new CalAIM Community Support (optional July 1, 2025; mandatory for Behavioral Health Population of Focus starting January 1, 2026). This provides up to six months of rental assistance — a significant development that partially closes the gap between "clinical services revenue" and "actual housing costs" that the Tenancy Bridge Guarantee is designed to bridge. The paper should acknowledge this development, even if only as a footnote, because it materially changes the landscape the paper describes.

3. **Missing: The IMD exclusion interaction.** The paper does not address how the 348-resident, three-pod tower avoids classification as an Institution for Mental Diseases (IMD) under 42 CFR §435.1010 (the ">16 beds" threshold). The CONSTRAINTS_REGISTER.md (C-01) addresses this by classifying the tower as "residential supportive housing, not clinical facility; services delivered via external managed care contracts." WP5 should cross-reference this classification explicitly, because the Tenancy Bridge Guarantee's CalAIM revenue stream is void if the facility is classified as an IMD — federal Medicaid cannot reimburse services for adults aged 21–64 in an IMD at all.

#### Citation Audit

| Citation Key | Verdict | Notes |
|---|---|---|
| `dhcs2025community` | **Confirmed** | URL resolves to DHCS Community Supports Policy Guide Volume 2 (April 2025). Real document. |
| `chcf2021pricing` | **Confirmed** | URL resolves to CalHPS-hosted CHCF summary of Community Supports payment guidance (October 2021). Real document. |
| `oha2024hrsn` | **Confirmed** | URL resolves to Oregon Health Authority HRS Waiver Updates (May 2024). Real document. |
| `nashp2024managedcare` | **Confirmed** | URL resolves to NASHP article on managed care housing integration. Real document. |
| `sen1999development` | **Confirmed** | Standard academic citation. Amartya Sen, *Development as Freedom* (1999), Oxford University Press. |
| `cote2002identity` | **Confirmed** | Côté & Levine, *Identity Formation, Agency, and Culture* (2002), Lawrence Erlbaum. |
| `drake2012individual` | **Confirmed** | Drake, Bond & Becker, *Individual Placement and Support* (2012), Oxford University Press. |
| `lepage2021individualized` | **Confirmed** | LePage et al., Medical Care, Vol 59 Suppl 2, pp S195–S198 (2021). Has volume/pages. |
| `tsemberis2004housing` | **Confirmed** | Tsemberis, Gulcur & Nakae, AJPH, Vol 94(4), pp 651–656 (2004). Has volume/pages. |
| `pager2003mark` | **Confirmed** | Pager, AJS, Vol 108(5), pp 937–975 (2003). Has volume/pages. |
| `mullainathan2013scarcity` | **Confirmed** | Mullainathan & Shafir, *Scarcity* (2013), Macmillan. |
| `keys1950biology` | **Confirmed** | Keys et al., *The Biology of Human Starvation* (1950), U Minnesota Press. |
| `arnsten2009stress` | **Confirmed** | Arnsten, Nature Reviews Neuroscience, Vol 10(6), pp 410–422 (2009). |
| `khantzian1985self` | **Confirmed** | Khantzian, AJP, Vol 142(11), pp 1259–1264 (1985). |
| `volkow2016neurobiologic` | **Confirmed** | Volkow, Koob & McLellan, NEJM, Vol 374(4), pp 363–371 (2016). |
| `ostrom1990governing` | **Confirmed** | Ostrom, *Governing the Commons* (1990), Cambridge University Press. |
| `hansmann1996ownership` | **Confirmed** | Hansmann, *The Ownership of Enterprise* (1996), Harvard University Press. |
| `spence1973job` | **Confirmed** | Spence, QJE, Vol 87(3), pp 355–374 (1973). |
| `arrow1973higher` | **Confirmed** | Arrow, Journal of Public Economics, Vol 2(3), pp 193–216 (1973). |
| `phelps1972statistical` | **Confirmed** | Phelps, AER, Vol 62(4), pp 659–661 (1972). |
| `olson1965logic` | **Confirmed** | Olson, *The Logic of Collective Action* (1965), Harvard University Press. |
| `cornforth1995patterns` | **Confirmed** | Cornforth, Economic and Industrial Democracy, Vol 16(4), pp 487–523 (1995). |
| `diprete2006cumulative` | **Confirmed** | DiPrete & Eirich, Annual Review of Sociology, Vol 32, pp 271–297 (2006). |
| `arulampalam2001unemployment` | **Confirmed** | Arulampalam, Economic Journal, Vol 111(475), pp F585–F606 (2001). |
| `schwarzer1995generalized` | **Confirmed** | Schwarzer & Jerusalem, *Measures in Health Psychology* (1995). |
| `defourny2010conceptions` | **Confirmed** | Defourny & Nyssens, Journal of Social Entrepreneurship, Vol 1(1), pp 32–53 (2010). |
| `battilana2014advancing` | **Confirmed** | Battilana & Lee, Academy of Management Annals, Vol 8(1), pp 397–441 (2014). |
| `galera2009social` | **Confirmed** | Galera & Borzaga, Social Enterprise Journal, Vol 5(3), pp 210–228 (2009). |
| `perotin2014what` | **Confirmed** | Pérotin, Co-operatives UK (2014). Grey literature, no volume/pages expected. |
| `white2008recovery` | **Confirmed** | White & Cloud, Counselor, Vol 9(5), pp 22–27 (2008). |
| `rotz2015economic` | **Confirmed** | Rotz, Maxwell & Dunn, Mathematica Policy Research (2015). Technical report. |

**Result: 31/31 citations confirmed. Zero fabricated. Zero unable to verify.**

#### Summary of Required Substantive Edits

1. **Line 136:** Replace "frequently prohibits" with "categorically prohibits" (or equivalent language making clear the room-and-board exclusion is federal, absolute, and non-variable).
2. **Line 136 (or new footnote):** Add acknowledgment of Transitional Rent as a new CalAIM Community Support (effective July 2025 optional / January 2026 mandatory for BH Population of Focus), noting it provides up to six months of rental assistance and materially changes the revenue landscape described in the paper.
3. **Line 136 or Section 4 generally:** Add explicit cross-reference to the IMD exclusion (42 CFR §435.1010) and the architectural classification decision (tower as residential supportive housing, not clinical facility) that keeps the CalAIM revenue stream viable. Without this note, a reader familiar with Medicaid law will immediately ask why a 348-bed facility with on-site clinical staff isn't an IMD.
4. **Line 166:** The Failure Modes section already identifies Medicaid reimbursement volatility as a risk. Confirm this section does not need updating given the Transitional Rent development — it appears adequate as written.

---

## WP3: Los Angeles Pipeline (SSRN 6579600)

### Session A: Substance (Claude Opus 4.6)

#### Stage 0 Numeric Findings

- **L713 `$50,000,000`**: False positive. This is a Phase 2 CapEx line item (2,000 residential modules × $25K/unit = $50M). Not the per-person annual cost metric flagged in WP1.
- **L731 `$17,400,000`**: False positive. This is 348 residents × $50K/yr gross municipal savings. Correctly derived from the CalMatters-verified $50K/yr per-person baseline.

#### LAHSA 2025 PIT Count Cross-Check

**Finding: The framing sentence at Line 316 contained two precision errors.**

The paper claimed "approximately seventy-five thousand total homeless with fifty-eight percent unsheltered yielding approximately forty-seven thousand." The finalized HUD-reviewed LAHSA 2025 data shows:
- Total homeless (LA CoC): **72,195** (not ~75,000)
- Sheltered: 24,745
- Unsheltered: **47,450** (65.7%, not 58%)

The downstream pipeline distribution table (L324-329) uses ~47,100 as its implicit base and is internally consistent (26% + 35% + 34% + 5% = 100%, all absolute counts verify). The error was isolated to the framing sentence, not the operational planning figures.

**Fix applied:** Corrected L316 to cite the finalized 72,195 total, approximately two-thirds unsheltered, yielding 47,450. Added explanatory note that the pipeline table applies estimated allocation percentages to an adjusted ~47,100 base for operational planning.

#### $50K/yr Per-Person Cost Verification

CalMatters reporting confirmed: a single chronically homeless person costs taxpayers approximately $50,000/yr across emergency, psychiatric, judicial, and sanitation operations. Cited as `calmatters_2026` — verified real.

#### $24B California Expenditure Verification

California State Auditor (April 2024) confirmed $24 billion spent on homelessness programs FY 2018-19 through 2022-23. Abstract claim verified.

#### Citation Spot-Check (8/63)

| Citation Key | Verdict | Notes |
|---|---|---|
| `lahsa_count_2025` | **Confirmed** | LAHSA 2025 PIT Count. Real. Finalized total: 72,195. |
| `calmatters_2026` | **Confirmed** | CalMatters homelessness funding analysis. Documents $50K/yr baseline. |
| `ucsf_bhhi_2023` | **Confirmed** | UCSF Benioff Homelessness and Housing Initiative, California statewide study. Real. |
| `laing_1960` | **Confirmed** | R.D. Laing, *The Divided Self* (1960). Real. |
| `dunbar_1992` | **Confirmed** | Robin Dunbar, neocortex/group size (1992). Real. |
| `giddens_1991` | **Confirmed** | Anthony Giddens, *Modernity and Self-Identity* (1991). Real. Ontological security source. |
| `lac_ceo_measure_a_2025` | **Confirmed** | LA County CEO Measure Alpha spending plan. Real. |
| `lac_homeless_initiative_2025` | **Confirmed** | LA County Homeless Initiative FY 2025-26 funding. Real. |

**Result: 8/8 spot-checked citations confirmed. Zero fabricated.**

#### Summary of Substantive Edits Applied

1. **Line 316:** Corrected LAHSA 2025 PIT Count framing from ~75,000/58% to finalized 72,195/~two-thirds/47,450. Added explanatory note for pipeline table's ~47,100 adjusted base.

---

## WP1: Stewardship Model (SSRN 5968756)

### Session A: Substance (Stage 3)

#### Stage 3 Numeric Findings

- Addressed a structural mathematical contradiction regarding the Efficiency Surplus and MDI Tower cost comparisons.
- The previous calculation relied on an unadjusted Tower Facility Expenditure ($9,000–$12,000) leading to an artificially high efficiency surplus ($33M–$82M).
- Recomputed the Efficiency Surplus using the fully-loaded MDI infrastructure cost ($24,000–$29,000, inclusive of amortized capital debt service) as mandated by the Capital Architecture.
- Expanded the Efficiency Surplus table to present dual scales: the 348-resident Singular Prototype (surplus of $0.35–$9.05 Million) and the 2,000-resident full build-out (surplus of $2–$52 Million).
- Explicitly stated in the prose that fixed staffing costs per resident do not improve beyond the three-pod scale due to the Mega-Tower Segregation Requirement.
- Reframed the One California Plaza site explicitly as the eventual 2,000-unit full build-out, with the 348-resident Singular Prototype serving as the initial deployment section gating further expansion.

## WP2: Surplus Capacity (SSRN 6211658)

### Session A: Substance (Stage 4)

#### Stage 4 Findings and Adjustments
- **No Deletions Required**: Verified that the manufactured housing/RV category established in WP2 is a valid, parallel category of surplus capacity. It does not contradict the commercial real estate tower architecture deployed in WP1/WP3. Sections 5 and 6 remain untouched.
- **Added Series Structure Clarification**: Appended a paragraph to Section 5 clarifying that while WP2 establishes both commercial real estate and manufactured housing as valid surplus categories, subsequent papers in the series specifically operationalize the commercial tower category for dense metropolitan environments (like LA). The manufactured housing model remains valid for other contexts.
- **Added Collateralized Infrastructure Equity Mechanism**: Added a paragraph to Section 9 (Transition Path) bridging the gap between the National Stability Utility's master-tenant (OpEx) model and WP1's claim about collateralized equity (CapEx). Explained that capturing the avoided $50,000/yr municipal emergency liability (`calmatters_2026`) via pay-for-success agreements allows the Utility to securitize this revenue stream into infrastructure equity, providing the financial backing for large-scale master leases.
- **Governance Caveat**: Explicitly noted that the securitization structure is preliminary and subject to independent financial review. Removed hard-coded repo file references (e.g., `GOVERNANCE.md \S11.B`) in WP1 and WP2 to maintain academic register.
- **Citation Added**: Added `calmatters_2026` to `ssrn-6211658_Citations.bib` to resolve LaTeX compilation errors.

## WP4: Human Layer (SSRN 6881539)
### Session A: Substance & Style (Stage 5)

#### Stage 5 Findings and Adjustments
- **Numeric Drift Resolution (Section 6)**: Identified severe legacy drift in Section 6 (Verification Metrics). The text previously relied on an outdated 154-resident pod scale, a 13-pod tower model, and the superseded \$33M-\$82M Efficiency Surplus range.
- **Scale Standardization**: Refactored the retention math to strictly align with the standardized 116-resident / 3-pod (348 total residents) Singular Prototype scale established in WP3 and WP1. 
- **Conservative Range Application**: Applied the full California State Auditor processing cost range (\$4,200 to \$8,700 per event, `ca_state_auditor_2021`) to a retention gain of 2 to 3 residents. This yields a conservative \$8,400 to \$26,100 avoided processing cost per pod, or \$25,200 to \$78,300 annually across the three-pod prototype.
- **Causal Claim Softening**: Softened the causal relationship between administrative retention savings and the multi-million dollar Efficiency Surplus. Clarified that administrative savings act as "one input into" the surplus rather than the "primary variable driving" it, establishing a baseline economic contribution.
- **Global Sweeps**: Verified WP4 contained the final forbidden word in the entire corpus ("rather than"). Fixed via strict style replacement ("Reimbursement rates are negotiated per plan. No binding statewide schedule applies."). Purged the final surviving legacy Efficiency Surplus figure from `09_glossary/Systemic_Dignity_Glossary.md`.

**Result: Corpus fully aligned. All five working papers reconciled, standardized against the Singular Prototype architecture, and style-hardened.**
