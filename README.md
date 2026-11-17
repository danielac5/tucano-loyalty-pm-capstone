# Tucano Loyalty — Project Management Capstone

End-to-end Project Management portfolio for **Tucano Loyalty**, a native mobile loyalty application (iOS & Android) integrated with X-POS across 6 Tucano Coffee locations in Chișinău, Republic of Moldova.

> **Main Deliverable:** [Capstone_Tucano_Loyalty.xlsx](./Capstone_Tucano_Loyalty.xlsx) *(19 integrated, formula-driven tabs — written in Romanian)*

---

## Project Overview

| Parameter | Value |
| :--- | :--- |
| **Delivery Methodology** | Hybrid (Predictive baselines & governance + 4 × 2-week Agile sprints) |
| **Timeline** | 02.11.2026 – 16.04.2027 (Public launch **J5**: 14.02.2027) |
| **Scope Baseline** | 78 work packages + 5 milestones (`1,923 h` total effort, 27 traced requirements) |
| **Estimated Work Cost** | `86,005 €` |
| **Initial Contingency Reserve** | `3,100 €` (covers active EMV of `2,930 €`) |
| **Cost Baseline (BAC)** | `89,105 €` |
| **Management Reserve** | `895 €` |
| **Approved Total Budget** | `90,000 €` |

---

## Workbook Architecture (19 Tabs)

* **Control & Executive Reporting:** `00 Index`, `00 Dashboard` (Live EVM metrics, traffic-light health indicators & S-Curve), `00 Setari` (single source of truth for exchange rates, thresholds, reserves & RM public holidays).
* **Initiation & Scope:** `01 Charter` (v1.1 with X-POS baseline & build-vs-SaaS TCO), `02 Stakeholderi` (15 stakeholders + Power/Interest matrix), `03 Cerinte` (R-01…R-27 + RTM), `04 Scop` (deliverables & acceptance criteria).
* **Schedule, Cost & Resources:** `05 WBS` (WBS Dictionary + PV/EV/AC using 0/100 and 50/50 rules), `06 Calendar` (3-point PERT $T_E$ + weekly Gantt), `07 Resurse` (USD→EUR rates, iOS/Android team structures & RACI matrix).
* **Risk, Quality & Governance:** `08 Riscuri` (Qualitative/Quantitative EMV & P×I matrix), `08b Probleme` (Issue Log), `09 Comunicare`, `10 PM Plan`.
* **Execution, Change Control & Closure:** `11 Status`, `11b Pontaj` (weekly timesheets & vendor invoices feeding AC), `12 Schimbari` (Change Log, CR-01 scope reserve trigger & contingency drawdowns), `13 Inchidere` (Closure Report, SLA warranty & Lessons Learned), `Calc` (weekly S-Curve engine).

---

## Key PM Highlights

* **Dynamic EVM & S-Curve:** Updating the reporting date in `00 Setari` and logging hours/invoices in `11b Pontaj` automatically recalculates `PV`, `EV`, `AC`, `SPI`, `CPI`, `EAC`, `TCPI`, and the S-Curve chart.
* **Scope Reserve Governance (CR-01):** Built-in scope buffer rule that defers the referral module (`WBS 4.6`) to Phase 2 if contingency consumption exceeds `75%` before milestone `J2`.
* **Contractual & Calendar Realism:** Incorporates Moldova statutory holidays, currency conversion (`1 USD = 0.87 EUR`), and a `+10%` vendor hours cap.
