# Proposal

## Introduction
Our goal is to tell the WYWT orgainization about where they can set up street teams near MTA subway stations so that they can get as much people to join their gala every summer. To do this, I'm going to do research on the peak time with the most people entering and exiting of the subway stations. This way the organization will know about where they can meet the most people so that the chances of getting someone to know about the organization are a lot higher.

## Preperation
### Data
The data I will be using is the MTA turnstile data found in http://web.mta.info/developers/turnstile.html. They keep track of C/A, UNIT, SCP, STATION, LINENAME, DIVISION, DATE, TIME, DESC, ENTRIES, EXITS. Not all of the attribute be useful to understand when there will be the highest peak of people entering and exiting of the station. There will be cleaning and manipulating of data to get a better results. You will expect me to work mostly on STATION, LINENAME, DATE, TIME, ENTRIES, EXITS attributes. Specifically, since the gala happens in the beginning of the summer, I will target most of the data during the first 5 month of the year. This could be a norm for the organization to provide applications for the gala event at the beginning of each year. So they can expect how many people will join the organization for the upcoming event during the Summer. The model then will predict the highest peak of each subways and use that subway stations to set up the street teams for the next year.

### Tools
In order to retrieve and aggregate the data, I will be using SQLite and Python to query and cleaning data. Then I will use seaborne to create visualizations so that you will able to easily see the different trends. If any other thoughts that could happened during our research, we can use other tools like Tableau to create dashboards for this project.

## MVP: Mininum Viable Product
My MVP will have graphs of time series of the subway station flow during specific time of days. Having this type of graph, I can make analysis on where to put street teams on specific stations. Anther graph I've decide is to create bargraphs on population overall during the beginning of the year. Also bargraphs for seasonal population to see at what seasons are more effective to set the street team on different stations. This will be a great starts for the project.

## Consideration
Some considerations that are outside my analyst on the MTA turnstile's data is about the setting of each subway station. Even though we can find the populated subway stations, setting up the street team might take a lot of spaces while there are many people moving in and out of the subway stations. Another consideration could be how to persuade people to get interested with the WYWT organization so people want to learn more about. Then we will need a way to keep track of each person's information who want to join the gala.


```python

```
