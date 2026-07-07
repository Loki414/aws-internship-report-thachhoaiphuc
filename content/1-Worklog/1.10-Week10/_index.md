---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Build basic patient and doctor interfaces for SmartHospital P2TB.
* Implement frontend service layer calling backend APIs (React/Vite).
* Test with seed data and fix frontend–backend data mapping issues.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Build basic patient interface <br>&emsp; + Personal info page, contact updates <br>&emsp; + Display CCCD, date of birth, gender, address, health insurance (BHYT) <br>&emsp; + Data states from Cognito/backend | 22/06/2026 | 22/06/2026 | SmartHospital P2TB – Frontend |
| 3 | - Build patient appointment booking interface <br>&emsp; + Select department, doctor, date, time slot <br>&emsp; + Submit booking request <br>&emsp; + Display existing appointments | 23/06/2026 | 23/06/2026 | SmartHospital P2TB – Frontend |
| 4 | - Build basic doctor interface <br>&emsp; + Doctor dashboard, appointment/waiting queue list <br>&emsp; + Patient info, search by CCCD <br>&emsp; + Open medical record to prepare exam slip | 24/06/2026 | 24/06/2026 | SmartHospital P2TB – Frontend |
| 5 | - Build frontend services calling backend APIs <br>&emsp; + Standardize Authorization token <br>&emsp; + Handle 401/403 errors, empty responses <br>&emsp; + Map backend data to UI components | 25/06/2026 | 25/06/2026 | SmartHospital P2TB – API spec |
| 6 | - Test frontend with initial seed data <br>- Fix mapping errors (patientId/maBN, recordId/maHSBA, doctorName/hoTen) <br>- Fix UI bugs: CloudFront refresh, wrong routes, wrong role menu, form not reset | 26/06/2026 | 26/06/2026 | SmartHospital P2TB – Frontend |

### Week 10 Achievements:

* Completed patient interface: personal info and appointment booking.

* Completed basic doctor interface: dashboard, waiting queue, CCCD search.

* Implemented frontend service layer with standardized token and API error handling.

* Identified and fixed data mapping issues between backend and frontend.

* Resolved UX bugs: wrong role routes, page not loading after CloudFront refresh.
