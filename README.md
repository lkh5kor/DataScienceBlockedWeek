Spring School on Data Science 2021

This project is the result of the case study conducted as part of Spring School on Data science 2021 held from 17th May 2021 to 21 May 2021. 



## Case study from Luxoft

### Initial Business Vision:
To create the global and the most complete database that provides the full scope of
biographical data of pilots, competition results for use of International Car Racing
Sports organization (ICRS) and its’ stakeholders.
### Key drivers to create the product are:
* Organizations (local and international Car Racing federations) were treating their data
in a different ways
* Incomplete data collection and data transfer approaches amongst the stakeholders
* External providers have the most complete info base, but the quality of their data does
not match expectations and the cost is high
* There was no global reliable source of bio and results data of the pilots
### The ICRS product is designed to solve these issues for the following key users:
* International Car Racing Sports organization
* Local and international Car Racing federations
* Sportsmen (pilots)
* Media (journalists, publicists)
### The main objectives of the project are:
* To allow updating, editing and sharing of biographical data and results of pilots. The top
goal would be to become the only source of trusted data (and not to use external
providers)
* To improve the quality of data supplied for Car Racing Sports stakeholders
* To integrate the product with as many local and international stakeholders (e.g.
communities) as possible
* To supply live data API formats to any data subscriber (e.g. Reuters)
* Nice to have: to create a monetization model (e.g. selling extra data to Media agencies
like CNN)
The main objective is to provide an overall data provision for the Car Racing Sports
organization and stakeholders
### Expected outcome:
* To have the database with the most comprehensive data migrated from different
sources, treated with different level of accuracy
* To be able to transfer data in real-time mode
* To generate reports for Media
* UI that could be used by key users


The project was implemented using python libraries such as flask, wtforms, flask_wtf (for local server creation and html reading, pandas for reading and handling the csv files and matplotlib for visualization. The csv files from [f1db] (http://ergast.com/mrd/db/#csv) was used as the dataset for the project and can be found in /src/f1db_csv folder.

The gui implementation can be found in /src/main.py.ipynb along with results are as shown in below images. 
![Home Page](https://github.com/lkh5kor/DataScienceBlockedWeek/tree/master/results/Home_page.jpg)
![Add new driver details](https://github.com/lkh5kor/DataScienceBlockedWeek/tree/master/results/New_driver_addition.jpg)
![New driver details](https://github.com/lkh5kor/DataScienceBlockedWeek/tree/master/results/New_driver_information.jpg)
![Country wise drivers plot](https://github.com/lkh5kor/DataScienceBlockedWeek/tree/master/results/Country_wise_drivers.jpg)
![Driver statistics](https://github.com/lkh5kor/DataScienceBlockedWeek/tree/master/results/Driver_statistics.jpg)



