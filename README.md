# Lab 1 — Requirements Engineering & UML Use-Case Modelling

**Problem Statement #61 — Sustainability & Green Tech**
**Household Carbon Footprint & Target Tracker**

## Overview

A green-living analytics tool where households log monthly utility consumption
(electricity in kWh, gas, and commute distance in km) to compute CO2e emissions
and track progress toward personal carbon-reduction targets.

**Actors**
- **Resident** — logs consumption, sets reduction targets, tracks progress.
- **Sustainability Coach** — reviews household data and provides recommendations.

**Core use cases**
- Log Monthly Consumption *(includes Compute CO2e Emissions)*
- Compute CO2e Emissions
- Set Reduction Target
- Track Progress Toward Target *(extended by Receive Milestone Alert)*
- Receive Milestone Alert
- View Historical Comparison Chart
- Review Household Data
- Provide Recommendations

## Deliverables

| Deliverable | File |
|---|---|
| Requirements Table (5 FR + 2 NFR) | [requirements/Household_Carbon_Tracker_Requirements_Table.xlsx](./requirements/Household_Carbon_Tracker_Requirements_Table.xlsx) |
| UML Use-Case Diagram | [diagrams/Household_Carbon_Tracker_UseCase_Diagram.pdf](./diagrams/Household_Carbon_Tracker_UseCase_Diagram.pdf) |
| Use-Case Flow Specification (Log Monthly Consumption) | [use_case_flow/Household_Carbon_Tracker_UseCase_Flow.docx](./use_case_flow/Household_Carbon_Tracker_UseCase_Flow.docx) |

## Notes

- The requirements table's **Comments** column is intentionally left blank for the
  peer-critique step of the lab and should be filled in after swapping with a classmate.
- The use-case diagram includes one `<<include>>` relationship (Log Monthly Consumption →
  Compute CO2e Emissions) and one `<<extend>>` relationship (Receive Milestone Alert →
  Track Progress Toward Target), as required by the lab brief.
