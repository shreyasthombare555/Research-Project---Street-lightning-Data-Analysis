# Research Project Street Lightning Data Analysis - (_Currently Working_)

# Project Introduction

A group of organizations came together to install smart lighting poles around the USF St. Petersburg campus. As of now, 4 poles are installed at two intersections around campus. These poles collect a variety of data including illumination, power use, atmospheric conditions (such as air quality, temperature, humidity, wind, rain, etc.), pedestrians, traffic, etc. This project involves analyzing these data sets, visualizing them, and more importantly, correlating them with other (external) data sets to uncover new (unknown) insights. One of the drivers of this project is to identify how these data can benefit society (i.e., “data for social good”). Findings of this project will be made available to the City of St. Petersburg to see how the city and its residents can benefit from investing in these poles. 

# Action Plan 

As of now I have accomplished the following project goals. 

i) Scrapped Air Quality Data collected using REST API calls from the smart streetlights using the cloud service platform.

2) Preprocessed scrapped data into a structured form.

3) Researched vital factors which contribute to the Air Quality (such as AQI, Pollutant concentration).

4) Used Tableau Prep/Python to develop automated data pipelines for fedding preprocessed data into a centralized database configured using MySQL.

5) Performed Feature Engineering in order to calculate AQI index, AQI index category, Pollutant Concentration(C).

6) Validated calculated fields using EPA AQI index calculator.

7) Populated pre-processed data tables into Tableau and develop insightful customary dashboards.

8) Correlated analyzed data with number of student enrollment/traffic emission data collected during the fall semester.

# Snapshot Dashboard 

**Fall Semester AQI data - Dashboard Link: ** https://public.tableau.com/profile/shreyas4686#!/vizhome/Air_Quality_Index_Fall_Semester_First_Week/Dashboard1

**Correlating Traffic Emission/Student Enrollment data with Air Quality data for entire fall 2020 semester - Dashboard Link: https://public.tableau.com/profile/shreyas4686#!/vizhome/AQIIndex_Student_Enrollment_WeekDays/AverageweekdaysAQIandStudentEnrollment**

# Technologies Used

i) Data Scrapping and Pre-processing: Python and MS Excel.

ii) Exploratory Data Analysis and Data VisualizationL: Tableau.

iii) Data Management: MYSQL, MYSQL Workbench, Tableau Prep. 

# Fututre Scope

i) Blending wind speed data with AQI data in order to forecast adverse weather condition and penetrate warning for high risk citizens.

ii) Scrapping noise and wind speed data from the street light installed at the St. Petersburg airport and consolidating it in the analysis. 

# Notes

_Please note, the jupyter notebook and the dashboards included in this repository represent a short glimpse of the analysis currently completed_
