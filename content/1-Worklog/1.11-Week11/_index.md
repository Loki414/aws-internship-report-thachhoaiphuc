---
title: "Week 11 Worklog"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives:

* Complete timeline-based medical record interface for patients.
* Complete doctor workflow for exam slips, prescriptions, and lab requests.
* Implement invoice and VNPay/MoMo payment interfaces.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Complete patient medical record interface <br>&emsp; + Display record ID by CCCD, patient info <br>&emsp; + Medical history summary, visit/exam/prescription/lab statistics | 29/06/2026 | 29/06/2026 | SmartHospital P2TB – Frontend |
| 3 | - Complete medical record timeline by visit/date <br>&emsp; + Cards for appointments, exam slips, lab results, prescriptions, invoices <br>&emsp; + Toggle filters by event type and date | 30/06/2026 | 30/06/2026 | SmartHospital P2TB – Frontend |
| 4 | - Fix record info mismatch between header and exam/lab/prescription details <br>&emsp; + Prioritize recordId/medicalRecordId/citizenId (CCCD) across all components | 01/07/2026 | 01/07/2026 | SmartHospital P2TB – Frontend |
| 5 | - Complete doctor exam slip interface <br>&emsp; + Select patient/record by CCCD <br>&emsp; + Enter symptoms, diagnosis, notes <br>&emsp; + Create exam slip, prescription, lab request via API | 02/07/2026 | 02/07/2026 | SmartHospital P2TB – API spec |
| 6 | - Complete patient invoice and payment interface <br>&emsp; + Pending/paid invoices, invoice details <br>&emsp; + Redirect to VNPay/MoMo via paymentUrl <br>- Payment result UI after returnUrl, reload invoices from backend | 03/07/2026 | 03/07/2026 | SmartHospital P2TB – Payment |

### Week 11 Achievements:

* Completed timeline medical record with filters by event type and date.

* Synchronized recordId/CCCD across all components, fixed record info mismatches.

* Completed doctor workflow: exam slips, prescriptions, lab requests.

* Implemented real payments via VNPay/MoMo with returnUrl/callback handling.
