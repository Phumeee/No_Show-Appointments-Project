Dataset Description

This dataset contains information on the medical appointments for 110,527 patients in Brazil. The aim of the data collection is to ascertain the factors that affect the ability of the patients to show up for their scheduled appointments. "No-shows", which can refer to patients who do not turn up for their appointments, can cost the hospital time, money and also disrupt the care of other patients. Therefore, this analysis is important to create tangible insights for the Brazil health care system to enable them understand the reason for "No-shows", and also make any necessary adjustments.

Decsription of the Variables

Having established these facts, we can then run through the description of the fourteen (14) variables in the dataset. These include:

SN	Variable	Description
1.	Patient ID	this is the identification number of the patients
2.	Appointment ID	this refers to the identification number for each appointment
3.	Gender	Male (M) or Female (F)
4.	ScheduledDay	the day the patient registered for the appointment. This occurs before the actual appointment day.
5.	AppointmentDay	the actual appointment day.
6.	Age	age of the patient
7.	Neighbourhood	this refers to the location for the appointment
8.	Scholarship	this refers to patients who are recipients of the "Bolsa Familia", a social welfare program of the Brazil Government
9.	Hipertension	is the patient hypertensive? True (1) or False (0)
10.	Diabetes	is the patient diabetic? True (1) or False (0)
11.	Alcoholism	is the patient an alcoholic? True (1) or False (0)
12.	Handcap	is the patient handicapped? True (1) or False (0)
13.	SMS-received	one or more messages sent to the patient: Yes (1) or No (0)
14.	No-show	is the patient a no-show? Yes (1) or No (0)

Questions for Analysis

According to equiscript, there are several reasons patients miss appointments. Some studies revealed that women are more likely to be a no-show. In noshowappointments, the description site for this dataset, an emphasis was placed on the fact that the proportion of the females was higher because they tend to be more health conscious compared to the men. The day of the week and month of the appointment also has an effect on patient no-shows. Additionally, reminders can be effective in preventing no-shows. Based on this information, this analysis will explore the following questions:

1. Are the females more likely to miss an appointment?
2. What variables are correlated with 'show'?:

Specific Variables of Interest:

1. Appointment day of the week
2. Appointment day of the month
3. Number of waiting days between the scheduled day and the appointment day
4. SMS reminder
