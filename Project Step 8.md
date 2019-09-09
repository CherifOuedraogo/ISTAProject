## Project Step 8

**ISTA420

Cherif Ouedraogo

Date: 8/18/2019


**Software Requirements Specification**

**Emphasis on the Functional requirements for a Graphical User Interface**

***
**Clean Water Project**

**1. Introduction**


This project step gives an overview of the different components of the project and the general requirements for each component.

_**Purpose**_

This part of the software requirement focuses on giving the detailed functional requirements of the graphical user interface.

_**Scope**_

The graphical user interface() which will be referred to as *GUI* throughout the rest of the document) will be used in conjunction with a database in order to access and keep track of personnel, locations, equipment and other miscellaneous components of a project.
This project will have 15 water stations in various locations, and each location will have its own personnel and equipment.
A user will use the GUI to have access to the database and be able to perform some queries based on his/her credentials.

**2. Graphical User Interface Functions**

The GUI will allow the user to create an account or log in to an existing account. The level of access will be determined based on the log in credentials.
The GUI will grant access or request  different credentials from the user. 
The GUI will be a portal linking the user to the database and present the user with the elements of the databases accessible to query.
The GUI will present options to submit queries to the database and allow the user to validate the query requests. 
The GUI will be able to render query results to the user or present a text box informing the user that no result were found.

**3. Users**

The GUI will have three categories of users with each user having a specified access to the database.
The first user will be any personnel from the maintenance team. They will have a restricted log in credentials that will limit them to access only the data pertaining to the water pumps, and the water stations in the database. The GUI will only display these tables when a personnel from the maintenance team has successfully logged in. The maintenance personnel can submit queries like Insert, Update or delete elements from the corresponding tables.
The second category of users will be the water station liaisons. They will have  separate credentials as well. Once logged in, they will have access to the personnel tables and the water station tables.
The final category of users will be the administrator of the project. With an administrator credential, the GUI displays all the components of the database. The administrator can perform all types of queries and print reports and other statistical data regarding the project.

**4. Constrains**

The GUI will need an internet connection in order to allow multiple locations access.
The user will need a computer and a web browser in order to deploy the GUI.
The database the GUI is connecting to must have data.

**5. Functional Requirements**


_**Requirement1**_

The GUI presents an initial page which prompts the user to sign in or create an account.
This initial page must have a section for each category of users. Each category will be required to create a username and password, and also to enter a valid email.


_**Requirement2**_

The GUI validates the credentials and stores the log in details for future operations and goes to the next page.


_**Requirement3**_

The GUI stays on the same page and prompts the user to enter valid credentials if no validations occurs.


_**Requirement4**_

The GUI establishes a connection with the database and grant access only the data available to the category of user.


_**Requirement5**_

The GUI displays diagrams of tables and menus bars for the user to search the database.


_**Requirement6**_

The user uses a pointing device to navigate through the diagrams and the drop-down menus.


_**Requirement7**_

The GUI collects all selections made by the user when the user clicks a submit-request button.


_**Requirement8**_

The GUI processes  the query and compiles the result based on the query details.


_**Requirement9**_

The GUI displays the results and offer the user to save it or print it. The GUI ask the user if  he/she would like to perform another query or log out.


_**Requirement10**_

The GUI reads the response of the user and either opens a new query session or closes the current session.


_**Requirement11**_

The user logs out and the GUI disconnects from the database.


_**Requirement12**_

The GUI displays the initial page with login sections and general information about the project.

