# Investigate a Dataset (Show and No Show of Patients for Medical Appointments)

## Introduction

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row. Our Task in here to import the data, cleand and analyze in order to get some facts about Show and No Show of Medical Appointment.

<h5>Context</h5>
A person makes a doctor appointment, receives all the instructions and no-show. Who to blame?
If this help you studying or working, please don´t forget to upvote :). Reference to Joni Hoppen and Aquarela Advanced Analytics Aquarela.

<h5>Content</h5>
110.527 medical appointments its 14 associated variables (characteristics). The most important one if the patient show-up or no-show to the appointment. Variable names are self-explanatory, if you have doubts, just let me know!

scholarship variable means this concept = https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia

14 variables

<h5>Data Dictionary:</h5>
<ul>
    <li>PatientId: Identification of a patient
    <li>AppointmentID: Identification of each appointment
    <li>Gender:Male or Female . Female is the greater proportion, woman takes way more care of they health in comparison to man.
    <li>Age: How old is the patient.
    <li>AppointmentDay: In which Day the patient schedule a date.
    <li>ScheduledDay: tells us on what day the patient set up their appointment.
    <li>Neighborhood’ indicates the location of the hospital.
    <li>Neighbourhood: Where the appointment takes place.
    <li>Scholarship:True of False . Observation, this is a broad topic, consider reading this article https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia
    <li>Hipertension: 0 or 1.
    <li>Diabetes: 0 or 1.
    <li>Alcoholism: o or 1.
    <li>Handcap: The Handicap status from 0 to 4.
    <li>SMS_received: 1 or more messages sent to the patient.
    <li>No-show: True or False.</li>
</ul>
<h5>Inspiration:</h5>
What if that possible to predict someone to no-show an appointment?

<h5>Scope:</h5>
Our scope in this investigation is to Assess, Clean, Investigate The Data and retreive answers for below questions:
<ul>
    <li>Research Question 1 (in General, regardless all other values, plot the percentage of Show and No-Show frequency!)</li>
    <li>Research Question 2  (How The Gender Type impacts the Show and No Show Frequency and Percentage!)</li>
    <li>Research Question 3 (How The Scheduled Weekday impacts the Show and No Show Frequency and Percentage!)</li>
    <li>Research Question 4 (How the Days difference between Appointment Day and Scheduled Day impacts the Show and No Show Frequency and Percentage!)</li>
    <li>Research Question 5 (Highest City has the Most Show!)</li>
    <li>Research Question 6 (How Scholarship impacts the Show and No Show Frequency and Percentage!)</li>
    <li>Research Question 7 (How Diseases impacts the Show and No Show Frequency and Percentage!)</li>
    <li>Research Question 8 (Does Handicap Grades affects the Show status!)</li>
    <li>Research Question 9 (How Alcoholism Status impacts the Show and No Show Frequency and Percentage!)</li>
    <li>Research Question 10  (Does Sending SMS to Patients affects the Show status!)</li>
    <li>Research Question 11 (Average Age of Show and No Show!)</li>
</ul>
