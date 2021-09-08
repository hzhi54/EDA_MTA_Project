# Proposal

## Introduction
Our goal is to tell the WYWT orgainization about where they can set up street teams near MTA subway stations so that they can get as much people to join their gala every summer. To do this, I'm going to do research on the peak time with the most people entering and exiting of the subway stations. This way the organization will know about where they can meet the most people so that the chances of getting someone know about the organization are a lot higher.

## Preperation
### Data
The data I will be using is the MTA turnstile data found in http://web.mta.info/developers/turnstile.html. They keep track of C/A, UNIT, SCP, STATION, LINENAME, DIVISION, DATE, TIME, DESC, ENTRIES, EXITS. Not all of the attribute be useful to understand when there will be the highest peak of people entering and exiting of the station. There will be cleaning and manipulating of data to get a better results. You will expect me to work mostly on STATION, LINENAME, DATE, TIME, ENTRIES, EXITS attributes. Specifically, since the gala happens in the beginning of the summer, I will target of most of the data during the first 5 month of the year. This way there will be a norm from the organization of applications they will recieve during the first 5 month interval for each year. The model then will predict the highest peak of each subways and use that subway stations to set up the street teams.

### Tools
In ordere to retrieve and aggretate the data, I will be using SQLite and Python to query and cleaning data. Then I will using seaborne to create visualizations so that you will able to easily see the different trends on different time. If any other thoughts that could happened during our research, we can use other tools like Tableau to create dashboards for this project.
