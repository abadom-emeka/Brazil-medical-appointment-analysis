# Brazil-medical-appointment-analysis


This project is a part of my submission for the Alx-t/Udacity Data Analysis Nanodegree Programme
#### -- Project Status: [Completed]

### Introduction
**Why do patients not keep their appointments?** An individual makes a doctor appointment, receives all the instructions and doesnt show up for the appointment. **Who or what do we attribute the blame to?** This project analyses the possible reasons of patients not showing up for their medical appointments)

#### Dataset
The dataset which contains informations on medical appointments collected in Brazil was obtained from the website https://www.kaggle.com/datasets/joniarroba/noshowappointments.


### Methods Used
* Data Cleaning and Wrangling
* Data Visualization
* Feature Extraction

### Technologies
* Python
* Numpy, Matplotlib
* Pandas, jupyter notebook
* HTML 

## Project Description

>  Patients who fail to show up to scheduled appointments or cancel at the last minute - giving the health center no opportunity to fill the appointment slot - are often referred to as no-shows. No-show appointments result in loss of time and money for the health center and disrupts continuity of care for patients. 
>  There are multiple reasons patients miss appointments. They may have forgotten, had transportation issues, or couldn’t get off work. Some patients' missed appointments are rooted in negative emotions or anxiety associated with going to the doctor. Some patients also report feeling disrespected by the health care system whether it be because of staff, wait times, or beliefs that their opinions or feelings are not taken into account. 

This project analyses some possible reasons for the no-show attitude among patients. Some of the questions posed and answered include
* Is there a disparity in showing up of appointments between males and females?
* Is there a day of the week that records high level of compliance of patients with respect to their appointments?
* Do patients belonging to specific age groups show up to appointments more than others?
* Does SMS reminders help patients visit the doctor at the appointed date?

## Conclusions

### Results
* Out of 110,526 patients who scheduled appointments, 88207(over 79.8%) patients showed up while 22319(about 20.2%) patients did not show up.
* Females make up about 65% of the dataset while males account for the remaining 35%.
* There isnt much disparity among the genders in showing up for appointments.
* Tuesday and Wednesday records the highest number of fixed date for appointment, Saturday records the lowest number of appointments and there are no appointments on Sunday.
* Seniors(ages 20 to 64) and toddlers(ages 2 to 4) have the highest tendency to show up for their appointments while teenagers(ages 13 to 20) have the lowest.
* Individuals with goverment welfare(scholarship) seem to actually show up less than those without welfare.
* Patients diagnosed with hypertension show up for their appointments than those who arent diagnosed with hypertension.
* Patients diagnosed with diabetes show up for their appointments than those who arent diagnosed with diabetes.
* There is some difference in the rate of showing up for appointments among the different categories of the physically-challenged(Handicapped).
* SMS Reminders are not very effective in getting patients to show up for their appointments.


### Limitations
* The entire dataset is a subset of the population and may possess some form of bias which may affect the inference from the analysis.
* Most of the variables are categorical,this hinders some bivariate and multivariate analysis that could have provided more insights.
* There are some findings that seem counter-intuitive. The SMS reminders was expected to show increase in patients showing up for their appointments but reverse was the case.


## References
* https://www.equiscript.com/blog/patient-no-shows
