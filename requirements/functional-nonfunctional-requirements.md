# Requirements — Online Appointment & Records System for a Local Clinic

## Requirements Gathering Techniques

Two techniques were used to gather requirements for this system:

- **Interview** — conducted with a clinic receptionist, using a structured 8-question protocol covering current booking process, common scheduling problems, and record-keeping challenges.
- **Questionnaire** — a Google Forms survey distributed to patients, covering current booking experience, satisfaction, and desired features in an online system.

## Functional Requirements

| ID | Requirement |
|---|---|
| FR-01 | The system shall allow patients to create an account with their basic details. |
| FR-02 | The system shall allow patients to view available slots and book online. |
| FR-03 | The system shall allow patients to cancel or reschedule an appointment. |
| FR-04 | The system shall send automatic reminders before an appointment. |
| FR-05 | The system shall allow receptionists to manage all appointments from a dashboard. |
| FR-06 | The system shall allow doctors to view a patient's visit history. |
| FR-07 | The system shall generate a billing invoice after a completed appointment. |
| FR-08 | The system shall allow receptionists to search patient records by name or ID. |

## Non-Functional Requirements

| ID | Category | Requirement |
|---|---|---|
| NFR-01 | Usability | The system should have a simple interface since not everyone is tech savvy. |
| NFR-02 | Performance | Available slots should load within a few seconds. |
| NFR-03 | Security | Patient records need to be protected with login credentials. |
| NFR-04 | Reliability | The system should stay up during clinic hours with barely any downtime. |
| NFR-05 | Scalability | The system needs to handle more patients as the clinic grows. |

## Major Existing-System Limitations

- Appointments only bookable by phone or in person
- Handwritten register prone to double-booking errors
- Paper patient files are difficult to search quickly
- No automatic reminder system, leading to missed appointments
- Manual billing calculations increase the risk of errors
