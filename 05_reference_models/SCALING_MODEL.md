# Scaling Model Reference

This document provides lookup tables for operators projecting SDI deployments at various scales. All figures derive from the engineering baselines established in WP6 and codified in PILOT-SPECIFICATIONS.md Section 6.

---

## 1. Single-Pod Baseline

| Parameter | Value |
|---|---|
| Community Ceiling (Dunbar Limit) | 150 |
| Permanent On-Site Staff (FTE) | 38 |
| Resident Capacity | 112 |
| ALMU Unit Size | 150 sq ft |
| Residential Square Footage | 16,800 sq ft |
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
| Loading / Logistics | Fixed | 4 |
| **Fixed Subtotal** | | **19** |
| **Total** | | **38** |

---

## 3. Multi-Pod Scaling Table

| Metric | 1 Pod | 2 Pods | 3 Pods (Max) |
|---|---|---|---|
| Total Residents | 112 | 224 | 336 |
| Variable Staff (Dedicated) | 19 | 38 | 57 |
| Fixed Staff (Shared) | 19 | 24 | 28 |
| Total Staff | 38 | 62 | 85 |
| Total Community (Staff + Residents) | 150 | 286 | 421 |
| Dunbar Pods | 1 | 2 | 3 |
| Gross Square Footage | 85,000 | 135,000 | 185,000 |
| Fixed Cost per Resident | Baseline | ~74% of Baseline | ~55% of Baseline |

**Constraint:** Maximum three pods per independent vertical pipeline. Beyond three pods, cognitive isolation in shared circulation infrastructure (elevators, airlocks) cannot be maintained.

---

## 4. Mega-Tower Segregation Model

For commercial mega-towers exceeding three pods, the building must be architecturally severed into independent sectors.

| Metric | 3-Pod Sector | 6-Sector Mega-Tower |
|---|---|---|
| Pods per Sector | 3 | 3 |
| Total Sectors | 1 | 6 |
| Total Pods | 3 | 18 |
| Total Residents | 336 | 2,016 |
| Total Staff | 85 | ~450 |
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
