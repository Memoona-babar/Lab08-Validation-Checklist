# Validation Run - Student B

## 1. General Information

- Project: MediTrack Appointment System
- Student: Arwa Ahmed
- Checklist Version: 0.1
- Start Time: 12:00
- End Time: 12:15
- Duration: 15 minutes

## 2. Checklist Results

| ID | Answer | Evidence / Reason |
|---|---|---|
| C-01 | Yes | All requirements have unique IDs from R-01 to R-14. |
| C-02 | No | R-07 combines cancellation, schedule updating, and receptionist notification in one requirement. |
| C-03 | No | R-02 uses the unclear word "quickly" without defining a specific response time. |
| C-04 | No | R-02 does not specify a measurable response-time limit. |
| C-05 | No | R-08 and R-09 do not provide enough detail for clear verification and testing. |
| C-06 | No | R-04 specifies 15-minute appointments, while R-05 allows doctors to set durations between 10 and 30 minutes. |
| C-07 | No | R-03 does not explain how the system handles two patients trying to book the same time slot. |
| C-08 | No | R-04 and R-05 provide different appointment-duration rules that need clarification. |
| C-09 | No | R-06 does not specify how long before an appointment reminders must be sent. |
| C-10 | No | R-09 does not clearly identify which user roles are allowed to access patient records. |
| C-11 | ? | R-01 mentions online booking, but it is unclear whether patients can view their existing appointments. |
| C-12 | No | R-08 says the system should be user-friendly for all age groups but does not define accessibility features for elderly users. |
| C-13 | No | R-10 allows receptionists to book walk-in appointments but does not explain how emergency walk-ins are prioritized. |
| C-14 | No | The SRS does not specify system performance requirements for busy periods such as Monday mornings. |
| C-15 | Yes | R-10 clearly states that receptionists can book walk-in appointments. |
| C-16 | No | R-14 allows doctors to view their daily schedules but does not explain how they manage appointment availability. |
| C-17 | No | R-12 mentions normal working hours but does not explain whether clinic administrators can configure them. |
| C-18 | No | R-09 mentions secure patient records but does not specify data retention or deletion rules. |

## 3. Uncertain Items

- C-11: It is unclear whether patients can view their existing appointments.
- C-17: It is unclear whether clinic administrators are responsible for setting working hours.

## 4. Conclusion

During the independent validation, I identified several issues in the MediTrack SRS. Some requirements are unclear, difficult to measure, or missing important details. I also found a possible conflict between appointment-duration requirements R-04 and R-05. The SRS should provide clearer rules for reminders, patient data security, accessibility, emergency walk-ins, and system performance. These improvements will make the requirements easier to understand, test, and validate.
