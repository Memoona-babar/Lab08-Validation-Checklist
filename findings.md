# MediTrack SRS Validation Findings

**Project:** MediTrack Appointment System  
**Validation Method:** AOUT Checklist Review  
**Reviewers:** Memoona Babar & Arwa Ahmed  
**Status:** Final  
**Checklist Version:** 0.1

## 1. Introduction

The MediTrack Software Requirements Specification (SRS) was reviewed independently by Student A and Student B using an 18-item AOUT validation checklist.

After completing their individual reviews, both students compared their results and discussed the identified issues. Both reviewers identified the same major findings and agreed on the recommendations listed in this report.

The purpose of the validation was to check the SRS for clarity, completeness, consistency, testability, and traceability.

## 2. Final Validation Findings

### F-01: Vague Performance Requirement
- **Requirement:** R-02
- **Issue:** The word "quickly" is not measurable.
- **Recommendation:** Specify a measurable response time, such as a maximum of 3 seconds under defined conditions.

### F-02: Conflicting Appointment Duration
- **Requirements:** R-04, R-05
- **Issue:** R-04 specifies appointments of 15 minutes, while R-05 allows doctors to set durations between 10 and 30 minutes.
- **Recommendation:** Clarify whether 15 minutes is the default duration or whether doctors can change it.

### F-03: Double-Booking Prevention Details Missing
- **Requirement:** R-03
- **Issue:** The SRS says double bookings must be prevented but does not explain how simultaneous booking requests will be handled.
- **Recommendation:** Define how the system will prevent two users from booking the same doctor's time slot at the same time.

### F-04: Reminder Timing Not Specified
- **Requirement:** R-06
- **Issue:** The SRS says reminders will be sent but does not specify when they will be sent.
- **Recommendation:** Define the reminder schedule, for example, 24 hours before an appointment.

### F-05: Cancellation Rules Need Clarification
- **Requirement:** R-07
- **Issue:** The requirement allows patients to cancel at any time but does not clearly explain the cancellation process and its rules.
- **Recommendation:** Clarify cancellation rules and how the system updates the doctor's schedule and notifies the receptionist.

### F-06: Accessibility Requirements Are Vague
- **Requirement:** R-08
- **Issue:** "User-friendly for all age groups" does not describe specific accessibility needs.
- **Recommendation:** Define suitable accessibility features and an alternative booking method for patients who cannot easily use online booking.

### F-07: Patient Data Security Details Missing
- **Requirement:** R-09
- **Issue:** The SRS says patient records will be stored securely but does not specify security measures or authorized access roles.
- **Recommendation:** Define access permissions and suitable security measures to protect patient medical information.

### F-08: Emergency Walk-In Process Missing
- **Requirement:** R-10
- **Issue:** The SRS allows receptionists to book walk-in appointments but does not explain how emergency walk-in patients will be handled.
- **Recommendation:** Add a clear process for handling emergency walk-in patients.

### F-09: Busy Monday Performance Not Defined
- **Requirements:** R-02, R-12
- **Issue:** The SRS does not define performance expectations for busy periods, especially Monday mornings.
- **Recommendation:** Specify expected simultaneous users or booking requests and acceptable response times during peak periods.

### F-10: Patient Data Retention Rules Missing
- **Requirement:** R-09
- **Issue:** The SRS does not explain how long patient records will be retained or how they will be securely deleted when appropriate.
- **Recommendation:** Define data retention and secure deletion requirements according to the clinic's applicable policies.

## 3. Comparison of Student A and Student B

Student A and Student B completed their checklist reviews independently. After comparing their results, both reviewers identified the same ten major findings.

| Comparison | Result |
|---|---|
| Student A review | Completed |
| Student B review | Completed |
| Common findings | F-01 to F-10 |
| Major disagreements | None reported |
| Final decision | Both reviewers agreed |

## 4. Conclusion

The validation identified issues related to unclear requirements, conflicting appointment duration rules, missing booking details, reminder timing, accessibility, emergency walk-ins, performance, and patient data protection.

Both reviewers agreed that these issues should be addressed before system development begins.

The SRS should be updated to make its requirements clear, complete, consistent, and testable. This will help improve the reliability and usability of the MediTrack Appointment System.

**Final Validation Status:** Completed by Student A and Student B.
