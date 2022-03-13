# Medical Appointment No Shows
> Why do 20% of patients miss their scheduled appointments?

> Data set from Kaggle: https://www.kaggle.com/joniarroba/noshowappointments

## By Mahmoud Madkour

## Table of Contents
<ul>
<li><a href="#introduction">Introduction</a></li>
<li><a href="#questions">Questions</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
<li><a href="#conclusions">Conclusions</a></li>
</ul>

<a id='introduction'></a>
## Introduction

A person makes a doctor appointment, receives all the instructions and no-show.

The most important one if the patient show-up or no-show to the appointment.

The main question we are trying to answer here is why 30% of patients miss their scheduled appointment.

We are trying to predict the most important factors that affect the attendance of the patient.

The dataset content 110.527 medical appointments its 14 associated variables.

***Data Dictionary***
1. **Patient_Id:** Identification of a patient.
2. **Appointment_ID:** Identification of each appointment.
3. **Gender:** Male or Female, Female is the greater proportion, woman takes way more care of they health in comparison to man.
4. **DataMarcacaoConsulta:** The day of the actuall appointment, when they have to visit the doctor.
5. **DataAgendamento:** The day someone called or registered the appointment, this is before appointment of course.
6. **Age:** How old is the patient.
7. **Neighbourhood:** Where the appointment takes place.
8. **Scholarship:** True or False.
9. **Hipertension:** True or False.
10. **Diabetes:** True or False.
11. **Alcoholism:** True or False.
12. **Handcap:** True or False.
13. **SMS_received:** 1 or more messages sent to the patient.
14. **No-show:** True or False.

<a id='questions'></a>
## Questions

- The main question we are trying to answer here is why 30% of patients miss their scheduled appointment.

***1. Univariate Exploration***
- **Q1:** What is the percentage of patients who show vs. who don't show?
- **Q2:** What percentage of patients are male and female and which one is more booked than the other?
- **Q3:** What is waiting days for Scheduled Day?
- **Q4:** Which the most booking Ages?
- **Q5:** In which Neighborhood are the most appointments taken?
- **Q6:** What percentage of patients are Scholarship, Hipertension, Diabetes, Alcoholism, Handcap and SMS_received

***2. Bivariate Exploration***
- **Q1:** What is the percentage of male and female patients who are already attending and who do not attend after booking?
- **Q2:** What is the relationship between waiting days and Show the patient?
- **Q3:** What is the most mandatory age to actually attend the booking?
- **Q4:** What is the five most mandatory neighborhood to attend booking already?
- **Q5:** What percentage of patients are Scholarship, Hipertension, Diabetes, Alcoholism, Handcap and SMS_received, And they have already made the booking?

***3. Multivariate Exploration***
- **Q1:** The Distribution of Age For 'Male, Female' and 'Show, Not Show'.
- **Q2:** Patients who received SMS compared to those who received SMS and showed up in 8 most booked neighborhoods
