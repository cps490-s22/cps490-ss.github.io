# cps490-ss.github.io
Public website for team CPS 490 Team 46's Capstone 2 project
# Capstone-II-Project Proposal

University of Dayton

Department of Computer Science

CPS 490 - Fall 2022

+ Dr. Nick Stiffler (2022 - )
+ Dr. Phu Phung (2018 - 2021)


# Project Topic


# Team members

1.  Natalie Stanton, stantonn3@udayton.edu
2.  Parker Steiskal, steiskalp1@udayton.edu
3.  Jake Jeske, jeskej1@udayton.edu
4.  Aaron Tilton, tiltona1@gmail.com
5.  Caleb Workman, workmanc1@udayton.edu
6.  Matt Esson, essonm2@udayton.edu
7.  Brandon Bullock, bullockb3@udayton.edu 


# Company Mentors

Name: Randy Wells

Email: randy@r-wells.com

Phone: (937) 474-0422


Name: Al Nels

Email: al@nels.us

Phone: (937) 902-9090


Balloon Federation of America - Wind Explorer Proposal 

Company address:
https://www.bfa.net/
1601 N.Jefferson Way
Indianola, Iowa 50125

## Project homepage

[Provide the URL to your team project homepage here]


# Overview

Describe the overview of the project with a high-level architecture figure (See an example below).


![Overview Architecture](https://capstones-cs-udayton.bitbucket.io/imgs/overview-sample.png "A Sample of Overview Architecture")

Figure 1. - A Sample of Overview Architecture of the proposed project.

# Project Context and Scope

Describe the context where the project will be used or deployed, i.e., the motivation of your project, and the scope of the project your team will develop. 
Discuss the interaction of the expected system in your project with people and the physical world.


# High-level Requirements

- Utilize phone on-board sensors in Portrait, Landscape, and Sideways orientations
  - Application must produce identical readings for each orientation
  -  Functionality and features identical to previous version of Android Wind Explorer application
- Wind data calculations identical to previous version of Android Wind Explorer application
- Aesthetics identical (to greatest extent possible) to the previous version of Android Wind Explorer application
- Data output/storage identical (format, file types, storage location) to the previous version
of Android Wind Explorer application 
  - Live post CSV information during in-progress wind reading to user-designated, personal Google Sheets account  
  - Generate output file (CSV, XML, and JPEG formats) and upload files to user-designated, personal Google Drive account 
  - Save generated output files (CSV, XML, and JPEG formats) locally on the phone to a user-designated folder for the user to access later
- User will have the ability to select a CSV file from a previous wind reading to re-display
the output within the Wind Explorer app (data table, hodograph)
- User will have the ability to select output in Above Ground Level (AGL) or Mean Sea Level (MSL)
- User will have the ability to select using GPS altitude for MSL reference or a fixed reference altitude.
- User will have the ability to select height rounding interval
- Pre-set or user entered Rate of Climb (ROC) coefficient for Pibal
- User will have the ability to select azimuth reference, True north, Magnetic north, Grid north or User offset
- User will have the ability to select speed reference, KPH, MPH, or Knots
- User will have the ability to select rate of climb units or feet per minute, feet per second, meters per second, or other units as found in the current Android app.
- User will have the ability to select using the phones compass sensor for all azimuth data,or use the phone compass sensor for the first reading and all subsequent reading are relative to the first by using the phones gyro sensors.
- User will have the ability to capture ‘North’ direction with a user button input to zero the azimuth reference and all readings will subsequently be based on the gyro sensors.
- User have the ability to select height units in feet or meters
- The initial data point as a reference for the first reading shall be displayed on the data table as “Surface” and display the azimuth at the time the data point was captured; speed does not need to be calculated or displayed for this measurement
- All output timestamps to utilize Coordinated Universal Time (UTC) versus the local time from the phone
- Pre-populated file names when saving files generated from the app shall be based on thestart date/time (in UTC) of the wind reading, in the following format: 
  - YYYYMMDD_HHMMSS_UTC.[file extension]
  - Example: 20200916_133427_UTC.csv
- Ability to hide specified features based on client specifications (Easter Egg)
- Testing required to verify any requirements
- Balloon Federation of America (BFA) server authentication for active BFA members (requires coordination with BFA server administrator) 
  - User entered BFA username/password at application startup 
  - Token issued from BFA server with expiration set to BFA membership expiration
- Application de-authorization at token expiration until successful reauthentication from BFA server 
  ○ New token issued
- Audio/visual countdown to indicate measurement is being taken based on client specifications
- The application must allow for updates in the future. The platform used to code the algorithms should allow for future maintenance including migration to future IOS and Android operating system versions.
- Results rounding based on client specifications 
  - Height - round to nearest whole number (based on user input) 
  - Direction - round to nearest whole number 
  - Speed - round to nearest 10th 
  - Azimuth - round to nearest whole number (if data will be shown) 
  - Elevation - round to nearest whole number (if data will be shown) 
  - Average Speed - round to nearest 10th (if data will be shown)

# Technology

Specify the development approach of your team, including programming languages, database, development, testing, and deployment environments. 

You also need to mention if there are any technical support and preferences from the company and if they provide an existing version of the application.

# Impacts

Describe impacts of the technologies that your team decided you use in this project, i.e., the arguments that your team use these technologies.


# Project Management

We will follow the Scrum approach, thus your team needs to identify the task in each sprint cycles, team meeting schedules, including this Fall and next Spring semester. The tenative schedule and sprint cycles for Spring 2022 are as follows. 

![Spring 2022 Timeline](https://capstones-cs-udayton.bitbucket.io/imgs/cps491timeline.png "Spring 2022 Timeline")


In this section, provide the link to your team bitbucket repository and Trello board. Your team must share the repo and the board with nstiffler1@udayton.edu

Github: 
Trello Board Link: https://trello.com/b/g8yH5Qc7/capstone2-project-board 

Include the screenshot of the timeline from your Trello board (with tasks). You can use the Trello template available here (only with timeline): [https://trello.com/b/uIgKfjr6/cps491-s21](https://trello.com/b/uIgKfjr6/cps491-s21)  


Below is the example of the Trello board timeline (Gantt chart) with sprint cycles but without tasks for Spring 2022: 

![Spring 2022 Timeline on Trello](https://capstones-cs-udayton.bitbucket.io/imgs/trello.png "Spring 2022 Timeline")



# Company Support

Based on your discussion with the company, describe here what they will support your team during this Fall and next Spring semester, and the communication plan with the company mentors. 
