
# MediTrack SRS - Final Validation Findings

## 1. Review Summary

Student A and Student B reviewed the MediTrack SRS using the 18-item validation checklist.

### Results

| Result | Student A | Student B |
|---|---:|---:|
| Yes | 2 | 2 |
| No | 16 | 16 |
| N/A | 0 | 0 |

Both sample reviews identify the same major problems.

## 2. Identified Problems

| ID | Requirement | Problem Found | Recommended Solution |
|---|---|---|---|
| F-01 | R-02 | Response time is not measurable. | Define response time in seconds. |
| F-02 | R-03 | Double booking prevention is unclear. | Define booking conflict prevention rules. |
| F-03 | R-04, R-05 | Appointment duration requirements conflict. | Define one consistent duration rule. |
| F-04 | R-06 | Reminder timing is missing. | Specify when reminders are sent. |
| F-05 | R-06 | Reminder delivery method is missing. | Specify SMS, email, or other methods. |
| F-06 | R-07 | Cancellation deadline is not defined. | Define cancellation rules. |
| F-07 | R-09 | Medical record access permissions are missing. | Define access for each user role. |
| F-08 | R-09 | Security controls are not specified. | Define security requirements. |
| F-09 | R-08 | Accessibility requirements are unclear. | Add features for elderly patients. |
| F-10 | R-10 | Emergency walk-in handling is missing. | Define emergency patient procedures. |
| F-11 | Not stated | Busy Monday morning demand is not addressed. | Define peak-time performance requirements. |
| F-12 | R-12 | Normal working hours are not specified. | Mention exact working days and hours. |
| F-13 | R-13 | Overdue payment policy is not explained. | Include the clinic payment policy. |
| F-14 | R-11 | Active appointment is not defined. | Define active appointment status. |
| F-15 | R-14 | Daily schedule information is not specified. | Define the details doctors can view. |
| F-16 | R-07 | Notification method and content are missing. | Define notification method and required information. |

## 3. User Requirements Validation

| User | Requirements Checked | Result |
|---|---|---|
| Patient | Booking, cancellation, reminders, accessibility | Partially covered |
| Doctor | Appointment duration and daily schedule | Needs improvement |
| Receptionist | Walk-in bookings and cancellation notifications | Needs improvement |
| Clinic Administrator | Payment policy and busy periods | Incomplete |
| Data Protection Officer | Patient record privacy and security | Incomplete |

## 4. Conclusion

The MediTrack SRS is not ready for final approval.

It contains unclear requirements, missing information, and conflicting appointment duration rules.

The most important problems are:

1. Double booking prevention.
2. Patient data privacy.
3. Appointment duration conflict.
4. Emergency walk-in handling.
5. Performance during busy hours.

The software company should update the SRS according to these findings and send it to CityCare Clinic for another validation review before signing the contract.
