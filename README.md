# NYC_Subway_System_EDA
Project1: Exploratory Data Analysis of MTA Turnstile Data:

This repository consist of Project-1 data and solution at Istanbul Data Science Academy following Metis curriculum. 
I am taking courses from Istanbul Data Science Academy which is the Google Cloud Authorized Training Partner in Turkey. This is the first project on my journey as a Data Scientist.

Project1 is about Exploratory Data Analysis (EDA) of Metropolitan Transportation Authority (MTA) Turnstile Data between November and May 2021 contains 5,242,282 rows and 11 columns or 6-month worth of data.


What is Exploratory Data Analysis (EDA)?

Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations.

The objectives of EDA are to:
* Suggest hypotheses about the causes of observed phenomena
* Assess assumptions on which statistical inference will be based
* Support the selection of appropriate statistical tools and techniques
* Provide a basis for further data collection through surveys or experiments

![Alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/b/ba/Data_visualization_process_v1.png/350px-Data_visualization_process_v1.png "img1")

Data Science Process flowchart


Goals:
* Want to find Where should I perform if I were a street artist?
* Planning optimal days and hours
* Find most popular Manhattan stations by turnstile entries 
* Find the busiest stations per day
* Find the time period of day with highest traffic per station.
* Analyze where should the street artist perform.


MTA Turnstile Data:

Data obtained from http://web.mta.info/developers/turnstile.html.

Field Descriptions:

C/A: Control Area (A002)

UNIT: Remote Unit for a station (R051)

SCP: Subunit Channel Position represents an specific address for a device (02-00-00)

STATION: Represents the station name the device is located at

LINENAME: Represents all train lines that can be boarded at this station

DIVISION: Represents the Line originally the station belonged to BMT, IRT, or IND

DATE: Represents the date (MM-DD-YY)

TIME: Represents the time (hh:mm:ss) for a scheduled audit event. The four hour intervals will differ from other stations due to the need for staggering to prevent flooding the system with audit readings all at once. Systemwide, stations have been set to begin audit transmittal between 00 to 03 hours, then every 4 hours after the first audit of the day.

DESC: Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours)

ENTRIES: The cumulative entry register value for a device.It is a 10 digit number representing the number of entries on the specific device since its inception. Other forms of initialization may occur upon roll-over of the counter, erasing the memory device containing the register data, and replacing the processing device of the turnstile.

EXITS: The cumulative exit register value for a device

RESULTS:

![Alt text](https://github.com/nuriyeakin/NYC_Subway_System_EDA/blob/main/Top5Station.png?raw=true "img2")

![Alt text](https://github.com/nuriyeakin/NYC_Subway_System_EDA/blob/main/Top5Stationby_Day.png?raw=true "img3")

![Alt text](https://github.com/nuriyeakin/NYC_Subway_System_EDA/blob/main/Top5_Heatmap.png?raw=true "img4")

