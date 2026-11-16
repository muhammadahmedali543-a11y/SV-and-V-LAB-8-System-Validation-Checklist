# MediTrack SRS – Validation Findings

## 1. Summary

The checklist review identified several problems in the MediTrack SRS. Some requirements are unclear, incomplete, or contradictory. The document needs improvement before approval.

## 2. Main Findings

| Finding ID | Related Requirements | Problem | Risk / Impact | Suggested Improvement |
|---|---|---|---|---|
| F-01 | R-03 | Double-booking prevention is not clearly explained. | Two patients may receive the same appointment slot. | Define conflict detection and simultaneous booking handling. |
| F-02 | R-04, R-05 | Appointment duration requirements contradict each other. | Incorrect scheduling may occur. | Define one consistent appointment-duration rule. |
| F-03 | R-02, R-12 | Response time and working hours are unclear. | Performance and availability cannot be properly tested. | Specify measurable response times and working hours. |
| F-04 | R-06 | Reminder timing and method are missing. | Patients may forget appointments. | Define reminder schedule and delivery method. |
| F-05 | R-07 | Cancellation rules are unclear. | Doctor schedules may be disrupted. | Define cancellation deadlines and procedures. |
| F-06 | R-08 | User-friendly is not measurable. | Elderly patients may face difficulties. | Add accessibility and usability requirements. |
| F-07 | R-09 | Security and access permissions are not explained. | Private medical information may be exposed. | Define role-based access and security controls. |
| F-08 | R-10 | Emergency walk-in handling is missing. | Emergency patients may be delayed. | Define emergency booking and priority procedures. |
| F-09 | R-11 | Active appointment is not defined. | Confusion may occur about the appointment limit. | Clearly define active appointment status. |
| F-10 | R-13 | Clinic payment policy is not provided. | Payment handling may become inconsistent. | Include or reference the payment policy. |
| F-11 | R-14 | Doctor schedule details are missing. | Doctors may not receive necessary information. | Define the information displayed in daily schedules. |
| F-12 | R-01 to R-14 | Administrator and data protection officer functions are missing. | Important responsibilities may not be supported. | Add requirements for both roles. |
| F-13 | R-01, R-02 | Monday morning peak workload is not addressed. | The system may become slow during busy hours. | Define peak workload and performance requirements. |

## 3. Stakeholder Coverage

### Patient
Booking, cancellation, reminders, accessibility, and privacy need improvement.

### Doctor
Appointment duration and daily schedule requirements need clarification.

### Receptionist
Walk-in handling, emergency patients, and cancellation notifications need improvement.

### Clinic Administrator
Administrative functions, working hours, and payment policies need clarification.

### Data Protection Officer
Medical record security and access permissions need to be defined.

## 4. Risks Identified

1. Double booking of appointments.
2. Patients missing appointments due to unclear reminders.
3. Unauthorized access to private medical records.
4. Elderly patients facing difficulties using the system.
5. Emergency walk-in patients being ignored or delayed.
6. Slow system performance during Monday mornings.
7. Incorrect scheduling due to conflicting appointment durations.
8. Inconsistent overdue-payment handling.

## 5. Conclusion

The MediTrack SRS covers basic appointment functions, but several requirements are incomplete and unclear. The clinic should request improvements before signing the contract. Special attention should be given to double-booking prevention, security, appointment duration, reminders, and emergency patient handling.

