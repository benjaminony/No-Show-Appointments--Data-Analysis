### INTRODUCTION
This project is basic data analysis of [Medical Appointment data](https://www.kaggle.com/datasets/joniarroba/noshowappointments) from doctor appointments in Brazil. The analysis looked at the effect of: gender (male or female), Age, Neighbourhood in relation to making (No_show - False) or not making appointments (No_show - True).

The relationship between `No_show` variable as dependent variable, and `Gender`, `Age`, and `Neighborhood` as independent variables, are explored in the project.

### DATASET
The dataset analysed, contains 110,527 samples of medical appointments having 14 variables listed below:
1. PatientId - identification of a patient.
2. AppointmentID - identification of each appointment.
3. Gender - male (M) or female (F).
4. ScheduledDay - the day someone called or registered the appointment before the appointment at the hospital.
5. AppointmentDay: the day of the actuall appointment, when they have to visit the doctor.
6. Age - patient age.
7. Neighbourhood - where the hospital is located.
8. Scholarship - whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
9. Hipertension - True or False.
10. Diabetes  - True or False.
11. Alcoholism - True or False.
12. Handcap - True or False.
13. SMS_received - 1 or more messages sent to the patient - True or False.
14. No-show - whether the appointment was a no-show (patient did not show up) one or not - True or False.

### FINDINGS
The following was observed from analysis done;
Males turned up better for appointment and were more younger than females who did so although, the dataset seem to contain more younger males than females.
The neighbohoods where the hospitals are located seem not to matter since the neighborhoods with lowest no-show and that with highest attendance both had proportionally high attendance to appointment.

### PROJECT ENVIRONMENT
Project was carried out in Anaconda environment using the following python packages:
 - JuPyter notebook
 - Pandas
 - Numpy
 - Matplotlib
 - seaborn