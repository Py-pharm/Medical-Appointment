# Medical-Appointment

## Introduction

Missed outpatient appointments are a common problem for clinics, and reducing their rate improves office efficiency, income, and resident education.

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

In this project, we intend to explore the dataset and identify specific reasons using the variables why some patients missed outpatient appointments and then provide insight into developing targeted approaches to reducing their rates.

### Data Dictionary

01 - PatientId - Identification of a patient

02 - AppointmentID - Identification of each appointment

03 - Gender - Male or Female

04 - Age - How old the patient is

05 - ScheduledDay - Date of Appointment Schedule

06 - AppointmentDay - Actual date of appointment

07 - Neighbourhood - Location of the hospital.

08 - Scholarship - True(1) or False(0) : Family allowance provided by the government of Brazil in an attempt to reduce short-term poverty.

09 - Hypertension -True(1) or False(0)

10 - Diabetes - True(1) or False(0)

11 - Alcoholism - True(1) or False(0)

12 - Handcap - True(1) or False(0)

13 - SMS_received -1 or more messages sent to the patient.

14 - No-show - ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.


## key Findings

- For patients whose the duration between the appointment schedule date and the actual appointment date are more than 2 days, an average of 2 SMSs shound be sent to the patients to improve appointment compliance.

- Patients who had chronic conditions like hypertension and diabetes tend to keep up to appointments knowing the consequence of not doing so, however, patients without these conditions should be reminded of their appointments to avoid leading to critical conditions.

- Being Enrolled in the scholarship program seem to make patients more likely to show up to the appointment.

- Most of the patients who did not show up to their appointment are below the age of 60.
