# Scaling Model Reference

This document provides lookup tables for operators projecting SDI deployments at various scales. All figures derive from the engineering baselines established in WP6 and codified in PILOT-SPECIFICATIONS.md Section 6.

---

## 1. Single-Pod Baseline

| Parameter | Value |
|---|---|
| Community Ceiling (Dunbar Limit) | 150 |
| Permanent On-Site Staff (FTE) | 34 |
| Resident Volume | 116 |
| ALMU Unit Size | 150 sq ft |
| Residential Square Footage | 17,400 sq ft |
| Program Space | 71,500 sq ft |
| Back-of-House Infrastructure | 13,500 sq ft |
| **Minimum Gross Square Footage** | **85,000 sq ft** |

---

## 2. Staffing Breakdown: Variable vs. Fixed

Staff roles split into two categories for multi-pod scaling. Variable staff remain dedicated to a single pod to preserve cognitive isolation. Fixed staff operate outside the intimate pod network and scale across the whole building.

| Role | Category | Single Pod FTE |
|---|---|---|
| Registered Nurses | Variable | 8 |
| Security / Floor Monitors | Variable | 8 |
| Social Worker / Case Manager | Variable | 1 |
| Intake Coordinator | Variable | 1 |
| Veterinary Technician | Variable | 1 |
| **Variable Subtotal** | | **19** |
| Kitchen Workers | Fixed | 8 |
| Facilities Workers | Fixed | 4 |
| Physicians | Fixed | 2 |
| Building Supervisor | Fixed | 1 |
| **Fixed Subtotal** | | **15** |
| **Total** | | **34** |

---

## 3. Multi-Pod Scaling Table

| Metric | 1 Pod | 2 Pods | 3 Pods (Max) |
|---|---|---|---|
| Total Residents | 116 | 232 | 348 |
| Variable Staff (Dedicated) | 19 | 38 | 57 |
| Fixed Staff (Shared) | 15 | 19 | 19 |
| Total Staff | 34 | 57 | 76 |
| Total Community (Staff + Residents) | 150 | 289 | 424 |
| Dunbar Pods | 1 | 2 | 3 |
| Gross Square Footage | 85,000 | 135,000 | 185,000 |
| Fixed Cost per Resident | Baseline | ~74% of Baseline | ~55% of Baseline |

**Constraint:** Maximum three pods per independent vertical pipeline. Beyond three pods, cognitive isolation in shared circulation infrastructure (elevators, airlocks) cannot be maintained.

---

## 4. Mega-Tower Segregation Model

For commercial mega-towers exceeding three pods, the building is architecturally severed into independent sectors.

### Whole-Pod Rounding Rule

Mega-tower capacity is calculated by dividing the target unit count by the pod resident volume (116) and rounding **up** to the nearest whole pod. Fractional pods are prohibited. A 2,000-unit target produces 2,000 ÷ 116 = 17.24 pods, rounded up to **18 pods**, yielding a realized capacity of **2,088 residents** and a total staff count of **612 FTE** (18 × 34). The rounding rule prevents the creation of under-populated pods that breach the Dunbar cognitive architecture by operating below the social density threshold required for community formation.

| Metric | 3-Pod Sector | 6-Sector Mega-Tower |
|---|---|---|
| Pods per Sector | 3 | 3 |
| Total Sectors | 1 | 6 |
| Total Pods | 3 | 18 |
| Total Residents | 348 | 2,088 |
| Total Staff | 76 | 612 |
| Independent Intake Airlocks | 1 | 6 |
| Independent Elevator Banks | 1 | 6 |
| Independent Street Entrances | 1 | 6 |

**Requirements per sector:**
- Physically walled Intake Airlock with dedicated street entrance
- Dedicated elevator bank serving only that sector's residential floors
- Zero physical access between sectors without exiting the building

---

## 5. Coverage Multiplier Reference

| Coverage Type | Multiplier | Rationale |
|---|---|---|
| 24/7 Continuous | 4.2 FTE | Three 8-hour shifts × 7 days, adjusted for PTO, sick leave, and vacation |
| Daytime + On-Call | 2.0 FTE | Primary daytime coverage with on-call overnight rotation |
| Daytime Only | 1.0 FTE | Standard business hours, five days per week |
