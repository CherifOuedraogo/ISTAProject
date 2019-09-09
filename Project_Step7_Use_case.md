## Name: ISTA420 Project

## Author: Cherif Ouedraogo

## Date: 8/10/2019

## Project Step 7

### USE CASE : Query database

### ACTORS:

#### -User

#### -Graphical User Interface referred to as GUI in the use case

#### -HTML page

#### Trigger: 

The user indicates the needs to query the database.

#### Preconditions

Database must have data

User must have credentials

User must have GUI installed and a web browser to display it

#### Post condition

User receives query results.

#### Normal Flow

1.The User Accesses GUI

2. The GUI is deployed and HTML page displays Login Window
3. The User Enters Credentials
4. Access is granted
5. GUI displays database with drop down menus for tables 
6. The User clicks on drop down menu and select tables to query data from
7. The User fills up the query request window with the specific information and clicks on the Enter button
8. The GUI accepts information from user and processes the query
9. The GUI renders query results and offers the user to either print the results or enter a new query
10. The user logs out of the GUI and closes the web browser

#### Alternate Flow

##### A. The user enters the wrong credentials 

  1.The GUI displays a colored text prompting the user to enter the correct credentials

  2.The use case goes back to step 3 of Normal Flow. 

##### B. The user enters information too vague to query tables

  1.The GUI displays a colored text prompting the user to enter more data on the highlighted rows of the   data collection window   

 2.User enters more information into specified rows

 3.The use case returns to step 8 of the Normal Flow 

##### C. The user tries to access a restricted table in the database

1. The GUI displays a message box specifying that the user's access is denied and prompts the user to use different credentials.
2. The use case continue to step 10 of the Normal case.