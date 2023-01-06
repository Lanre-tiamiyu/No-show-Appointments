# No-show-Appointments

## Introduction

### Dataset Description 

> This dataset collects information from 100k medical appointments and is focused on the question of whether or not patients show up for their appointment. The data is sourced from Kaggle. A number of characteristics about the patient are included in each row. The variables of the dataset are :

PatientID------- Patient's identity number

AppointmentID--- Patient's appointment number

Gender---------- Patient's Gender ("M" for Male, "F" for Female)

ScheduledDay---- The date and time patients booked their appointment

AppointmentDay-- The date and time patients were to show up for their appointment

Age------------- Patient's age

Neighbourhood--- Location of the hospital

Scholarship----- Whether or not a patient is enrolled in Brasilian welfare program (0= No, 1= Yes)

Hipertension---- Whether or not the patient is hypertensive (0= No, 1=Yes)

Diabetes-------- Whether or not the patient is diabetic (0= No, 1=Yes)

Alcoholism------ Whether or not the patient consumes alcohol (0= No, 1=Yes)

Handcap--------- Whether or not the patient is handicapped (0= No, 1=Yes)

SMS_received---- Whether or not the patient recieved SMS notification (0= No, 1=Yes)

No-show--------- Whether or not the patient showed up for their appointment ("No"= Showed Up, "Yes"= Did Not Show Up)


## Question(s) for Analysis
The following questions were addressed:

1. What is the distribution of patients that showed up and did not show up for appointments based on the following factors: diabetic, gender, welfare program, hypertensive, alcohol, sms notifications?

2. Which gender has the lowest and highest no-show rate?

3. Which day of the week receives more appointments? And which has the highest no-show rate?


## Observations and Conclusions
During my investigation, I discovered the following: 
    
    Approximately 20% of the patients in the sample did not attend their visits. The majority of the patients were females, young, did not have a scholarship, and were not disabled. The majority of the patients made appointments on Wednesdays and Tuesdays. People missing appointments might be due to a variety of circumstances. The factors examined in the investigation were age, scholarship, gender, receiving as SMS, and the day of the week the appointment was scheduled.

The vast majority of patients do not drink alcohol, and majority do not have diabetes or hypertension.


## LIMITATION:

- The handcap data does not specify the type of disability considered.
- The data are for a short period of the year 2016. If we had data for the whole year, or even for other years, we could have seasonality analyzes.
