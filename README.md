# SAT-Score-New-York-City-School
Analyzing SAT Scores Data of New York City High School

The SAT, or Scholastic Aptitude Test, is an exam that U.S. high school students take before applying to college. 
Colleges take the test scores into account when deciding who to admit, so it's fairly important to perform well on it.
The test consists of three sections, each of which has 800 possible points. The combined score is out of 2,400 possible points (while this number has changed a few times, the data set for our project is based on 2,400 total points). Organizations often rank high schools by their average SAT scores. The scores are also considered a measure of overall school district quality.

New York City makes its [data on high school SAT scores](https://data.cityofnewyork.us/Education/SAT-Results/f9bf-2cp4) available online, as well as the [demographics for each high school](https://data.cityofnewyork.us/Education/DOE-High-School-Directory-2014-2015/n3p6-zve2).

Here are the links to all of the data sets we'll be using:

* [SAT scores by school](https://data.cityofnewyork.us/Education/SAT-Results/f9bf-2cp4) - SAT scores for each high school in New York City
* [School attendance](https://data.cityofnewyork.us/Education/School-Attendance-and-Enrollment-Statistics-by-Dis/7z8d-msnt) - Attendance information for each school in New York City
* [Class size](https://data.cityofnewyork.us/Education/2010-2011-Class-Size-School-level-detail/urz7-pzb3) - Information on class size for each school
* [AP test results](https://data.cityofnewyork.us/Education/AP-College-Board-2010-School-Level-Results/itfs-ms3e) - Advanced Placement (AP) exam results for each high school (passing an optional AP exam in a particular subject can earn a student college credit in that subject)
* [Graduation outcomes](https://data.cityofnewyork.us/Education/Graduation-Outcomes-Classes-Of-2005-2010-School-Le/vh2h-md7a) - The percentage of students who graduated, and other outcome information
* [Demographics](https://data.cityofnewyork.us/Education/School-Demographics-and-Accountability-Snapshot-20/ihfw-zy9j) - Demographic information for each school
* [School survey](https://data.cityofnewyork.us/Education/NYC-School-Survey-2011/mnz3-dyi8) - Surveys of parents, teachers, and students at each school

In this project we did an extensive data cleaning of New York SAT Scores data set

The data cleaing steps includes but are not limited to:
* Converting to numeric
* Extracting vale
* Standardizing colums
* Condensing our data
* Combining our data

## Goal
To determine the relationship between SAT Scores and other variables

## Methodology

This analysis will use descriptive statistics (e.g. mean, correlations, z-score) and data visualizations (e.g. scatter plots, bar charts, maps) to explore the following datasets on NYC high schools:

## Results
At the end of our analsis here are our findings:
* The higher the safe the school is as perceived by students, the higher the SAT Scores
* Schools with high percentage of students learning English have low SAT Scores i.e students who recently moved to the United States
* Students from Science, Technical and Liberal Arts Schools perform better in SAT Scores irespective of Safety, Race and Gender
* SAT Scores are not fair to Black and Hispanic students
* Asian students are highly represented with High SAT Scores

## Installing Packages
__folium requirements__

branca, jinja2 and requests.
* $ pip install folium 
or 
$ conda install folium -c conda-forge
* $ pip install plotly==4.9.0
or conda
$ conda install -c plotly plotly=4.9.0
