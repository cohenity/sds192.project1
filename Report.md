## Introduction:
The dataset used in this project is titled “Emergency Department Volume
and Capacity.” It was created by the Department of Healthcare Access and
Information, and contains data collected from California hospital
emergency departments to evaluate the relationship of hospital
encounters to treatment stations. This dataset contains 12,849
observations of 18 variables. Each observation represents a different
hospital and the variables in the dataset are the OSHPD ID, hospital
name, county, hospital system, range of emergency department treatment
stations, ownership category, area designation, whether it is teaching
or non-teaching, health condition category, total number of emergency
department encounters, number of treatment stations, number of patients
for health condition category, latitude, longitude, if it is in a
primary care shortage area, if it is in a mental health care shortage
area, number of patients per station, and the year of the data. The
variables of interest in the dataset are number of treatment stations
(EDStations), and total number of emergency department encounters
(Tot\_ED\_NmbVsts), both of which are numerical variables. This project
is guided by the question: how does capacity to treat patients in
emergency departments in urban areas with restricted access to primary
care vary based on hospital ownership, year, and county? To answer this,
I have condensed the Emergency Department Volume and Capacity dataset
into a smaller dataset titled Urban Shortage Areas
(urban\_shortage\_areas.csv). This dataset contains 1691 observations of
10 variables, with no missing values. This dataset only contains data
from urban hospitals in primary care shortage areas. The variables in
Urban Shortage Areas are number of patients per station, if it is in a
primary care shortage area, number of treatment stations, total number
of emergency department encounters, area designation, ownership
category, year, county, average number of emergency department
encounters, and average visits per station. The variables of interest
for this project are number of treatment stations and total number of
emergency department encounters, both of which are numerical variables.
## Plot 1: 
This plot displays the relationship between the number of
stations in an emergency department and the average number of patients
per station in emergency departments. This plot shows that emergency
departments with less stations tend to take on higher quantities of
patients. This indicates that emergency departments in urban areas with
restricted access to primary care may be overcrowded, as hospitals with
fewer stations likely are unable to accommodate large quantities of
patients. Overcrowding likely decreases the quality of care provided,
increases wait times, and causes hospital workers to be overwhelmed. 

## Plot 2: 
Plot 1 told us that hospitals with a low number of stations and a
higher quantity of patients likely results in a decreased quality of
care, plot 2 indicates whether hospital ownership has any correlation to
quality of care by examining the relationship between the average number
of patients per facility and number of stations for hospitals that are
owned by the government, nonprofits, or investors. This plot shows that
government hospitals likely have the greatest capacity to provide higher
quality care, as they have a comparatively high number of stations for
the number of patients treated. Nonprofit hospitals likely have a worse
capacity to provide high quality care as they have a comparatively high
number of patients for the number of stations available. 

## Plot 3: 
Plot 3 shows the relationship between the number of emergency department
stations and the total number of patients treated in the emergency
department by year. The three boxplots show a decline in the quality of
care provided by emergency departments between 2021-2023. In 2021 there
was a higher number of emergency department stations with a lower number
of patients, and in 2023 there was a lower number of emergency
department stations with the highest total number of patients. 

## Plot 4: 
This plot displays the average number of emergency department visitors
per station in 15 different California counties. This plot shows that
Los Angeles county had the highest number of emergency department
patients per station by a large margin. Knowing that Los Angeles county
is the most populous county in California, and considering that the data
is only from hospitals in areas with restricted access to primary care,
the plot indicates that people living in more populated areas may have
worse access to primary care, and are likely being provided a lower
quality of care in emergency departments. 

## Conclusion:
Through the four data visualizations, I have found that emergency departments 
with less stations and higher numbers of patients are more likely to provide
patients with a lower quality of care. Based on that, it can be seen
that in California, from 2021-2023, quality of care in urban hospitals
in restricted primary care access areas has declined. This decline in
quality mainly affects those living in more populated areas, as they are
more likely to have restricted access to primary care and overcrowded
emergency departments. I have also found that government owned hospitals
are likely to provide a higher quality of care than nonprofit or
investor owned hospitals, from this we can guess that in Los Angeles, it
is likely that many hospitals are not government owned. Though this data
does provide helpful insight into how factors like location and
restricted access to primary care can affect the quality of treatment in
emergency departments, the data is skewed as over half of the hospitals
from where data was taken were in Los Angeles county. By having a
majority of the data be concentrated in one location, an accurate
picture of the state of emergency departments in the whole of
California. I also do not provide a comparison between hospitals in
areas with adequate access to primary care, which could provide
beneficial insight into whether or not the treatment in the hospitals I
evaluated is comparatively worse.
