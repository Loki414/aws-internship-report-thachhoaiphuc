---
title: "Week 9 Worklog"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Week 9 Objectives:

* Begin implementing the **SmartHospital P2TB** project — a hospital management system on AWS Serverless.
* Analyze user experience and design frontend architecture by Patient / Doctor roles.
* Prepare medical record layout, data mapping, and CCCD display conventions.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Analyze UX for Patients and Doctors <br>&emsp; + Define screens: login, registration, dashboard <br>&emsp; + Appointment booking, personal info, medical records <br>&emsp; + Lab results, invoices, waiting queue, exam slips, prescriptions | 15/06/2026 | 15/06/2026 | SmartHospital P2TB – Proposal |
| 3 | - Design role-based frontend routes <br>&emsp; + Patient → patient portal after login <br>&emsp; + Doctor → doctor interface <br>&emsp; + Role-appropriate sidebar/menu | 16/06/2026 | 16/06/2026 | SmartHospital P2TB – Proposal |
| 4 | - Design medical record layout <br>&emsp; + One patient – one record book, multiple medical events <br>&emsp; + Appointments, exam slips, lab results, prescriptions, invoices, medical documents | 17/06/2026 | 17/06/2026 | SmartHospital P2TB – Proposal |
| 5 | - Identify frontend data requirements from backend <br>&emsp; + patient/doctor profile, appointments, medical record <br>&emsp; + examinations, prescriptions, lab results, invoices <br>&emsp; + ledger verification result | 18/06/2026 | 18/06/2026 | SmartHospital P2TB – API spec |
| 6 | - Plan UI state handling: loading, empty, API error, expired token <br>- Standardize CCCD/recordId display conventions <br>- Summarize Week 9 | 19/06/2026 | 19/06/2026 | SmartHospital P2TB – Proposal |

### Week 9 Achievements:

* Completed UX analysis and screen list for Patient and Doctor roles.

* Designed frontend routes and menu structure by role.

* Defined timeline medical record model and frontend–backend data mapping.

* Standardized CCCD/recordId display conventions to avoid ID mismatches across pages.

* Planned handling for critical UI states (loading, empty, error, expired token, missing blockchain block, pending payment gateway).
