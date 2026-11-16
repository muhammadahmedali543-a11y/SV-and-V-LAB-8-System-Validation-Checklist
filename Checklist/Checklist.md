
# MediTrack SRS Validation Checklist 

**Answer Rules:**
- Yes = The requirement is adequately addressed.
- No = The requirement is missing, vague, or incomplete.
- N/A = The question is not applicable.

| ID   | Item | Answer | Evidence | Where question came from |
|      |      |                              |                                       |                                         |
| C-01 | Does the SRS define a measurable response-time limit for booking requests? | No | R-02 says "quickly" but gives no time limit. | Testability and performance risk |
| C-02 | Does the SRS explain how simultaneous booking requests for the same slot are handled? | No | R-03 does not explain conflict handling. | Double-booking risk |
| C-03 | Does the SRS define one consistent appointment-duration rule? | No | R-04 says 15 minutes, while R-05 allows 10–30 minutes. | Contradiction check and doctor needs |
| C-04 | Does the SRS specify when reminders must be sent? | No | R-06 does not mention reminder timing. | Missed appointment risk |
| C-05 | Does the SRS identify the reminder delivery method? | No | R-06 does not mention SMS, email, or notifications. | Completeness and patient needs |
| C-06 | Does the SRS define a cancellation deadline for patients? | No | R-07 allows cancellation at any time without defining a cancellation deadline. | Schedule disruption risk |
| C-07 | Does the SRS specify which roles may view patient medical records? | No | R-09 does not define access permissions. | Privacy risk and data protection officer needs |
| C-08 | Does the SRS specify an access-control mechanism for protecting patient records? | No | R-09 only says records are stored securely. | Security risk |
| C-09 | Does the SRS define how elderly patients can use the system? | No | R-08 only says user-friendly for all age groups. | Elderly patient needs |
| C-10 | Does the SRS define a priority rule for emergency walk-in patients? | No | R-10 does not mention emergency handling. | Emergency patient risk |
| C-11 | Does the SRS define what an active appointment means? | No | R-11 does not explain the meaning of active. | Ambiguity and patient needs |
| C-12 | Does the SRS state the clinic's normal working hours? | No | R-12 does not provide actual working hours. | Testability and receptionist needs |
| C-13 | Does the SRS identify the clinic policy for overdue payments? | No | R-13 refers to a policy that is not provided. | Clinic administrator needs |
| C-14 | Does the SRS define a measurable system availability target? | No | R-12 does not provide an uptime percentage. | Availability risk |
| C-15 | Does the SRS define a maximum response time during Monday morning peak hours? | No | R-02 gives no peak-period response-time target. | Monday morning performance risk |
| C-16 | Does the SRS specify what information doctors can see in their daily schedule? | No | R-14 does not define schedule details. | Doctor needs and privacy |
| C-17 | Does the SRS define at least one function for the clinic administrator? | No | No requirement describes administrator functions. | Stakeholder coverage |
| C-18 | Does the SRS define at least one function for the data protection officer? | No | No requirement describes data protection officer functions. | Stakeholder coverage |
