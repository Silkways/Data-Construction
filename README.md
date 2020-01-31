# Data_Construct
Flatiron Module 2 Project - Data Engineering

General Objective: 

The purpose of this project is to start interacting with different databases and use different forms of code to get access to data. Additionally, we are interacting with both SQL / NoSQL databases and work with an API from a weather website provide: DarkSky: https://darksky.net/

Data: 

The data set we are provided is the following: https://www.kaggle.com/laudanum/footballdelphi

This data set contains four tables: 
  - Matches: all football matches of several seasons 
  - Teams: German and English league team 
  - Unique Teams: Teams and a unique ID assigned to cover naming convention issues
  - Teams in Matches: matches associated with team unique ID 

Primary Goals: 

Construct data in such a way as to get the following features:

  - The name of the team
  - The total number of goals scored by the team during the 2011 season
  - The total number of wins the team earned during the 2011 season
  - A histogram visualization of the team's wins and losses for the 2011 season (store the visualization directly)
  - The team's win percentage on days where it was raining during games in the 2011 season.

Secondary Goals: 

develop interaction with Mongo Database and store the results in Mongo - both data and visualizations

Technical Document and Repository Strcuture: 

My document is divided in eight distinctive parts which outline the process of work from importing the data to storing the endresults in Mongo DB. 

The Git repo contains:
   - Technical document (main.ipynb) which is a concise review of my work
   - Test document (Project_Workbook.ipynb) which is a more exhaustive and less structured version of the work
   - SQL Database (database.sqlite) containing the relevant support tables 
   - An exhaustive data set containing weather data (final_weather_set.csv) stored to avoid having to use too many API calls 
   - An image summarising results used for the conversion to base64 and storage to Mongo
 
 Conclusion / Follow-ups: 
 
 Project completed and provided interesting insights in terms of structuring data and working with a diverse set of tools. 
 For future iterations, classes should be included and used more frequently to avoid repetitive code. 
 Visualisations should be  more numerous and split by team. 
 
 
