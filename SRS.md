# Software Requirement Specification

## ExamRelief

### 1. Introduction

#### 1.2 Purpose

The purpose of this document is to provide a set of requirements for a mobile app that will allow Students to track their deadlines, create a study timetable and for them to receive information concerning study tip as well as physical and mental health.

#### 1.3 Scope

The application will allow users to:

- Add to the app, and then view a list of their upcoming deadlines
- Create in the app, and view a timetable for their self study
- View lists of study techniques and study tips
- View articles and advice about mental health management as well as recipes and exercises
- Pin deadlines and health and study information to the apps home screen

All information in the app will be stored offline, but the health and study information will be updated by a remote server.

#### 1.4 Definitions

**CSV**: Comma separated Values

**HTML**: Hypertext Markup Language

**UI**: User Interface




### 2. Overall Description

#### 2.1 Product Perspective

The need for this app is due to the high mental health issues that students experience especially around exam time. It is a serious issue that need to be combatted. The app can be broken into 2 ways to  combatting this issue.

<u>Management of workload</u>

The deadline viewer, study timetable and study tips all aim to help students manage their exam revision time and revise more effectively. If the app provides tools for  students to more easily manage their workload then this should reduce stress and potentially anxiety, improving mental health. The app should also should improve performance if it impacts the students revision practises in the intended way.

<u>Management of mental health</u>

The health list aims to help users manage their mental health better. This will include mental health exercise, techniques to reduce anxiety and other tips for dealing with mental health. Many studies have linked physical health to mental health, and stressed out students are very susceptible to neglecting their physical health during exam periods. Therefore the health food will also contain easy recipes and physical exercises that can be done at home to help improve general wellbeing.

#### 2.2 Operating Environment 

- The app will be released for mobile phones on the android platform
- It requires any Android release from Lollipop 5.0.0 upwards
- It can be used internationally
- The app will be able to launch and function to access basic features without internet connection
- The app will require an internet connection to update the information and will be connected to servers that release health content

#### 2.3 Design and Implementation Constraints

- As the app is targeted at android phones, it will have to be written in Java
- All libraries must be free and allow software to be sold that use the library
- It will use a materiel and modern UI to make it easier to market to students

#### 2.4 Assumptions and Dependencies

- The app will assume that the user base is in the Uk and speaks English
  - Timetable and deadlines will track time using a BST or GMT timezone
  - UI text will be in English

- The app will assume User base is students and have experience using mobile apps
  - UI will be brightly coloured with a modern simple design
  - UI won't have many instructions or prompts
- The app will assume the users university timetables lectures in one hours slots
  - Import of University calendar will only allow this format.


### 3. System Features
#### 3.1 Functional Requirements

**FR001**: The app will open to the 'Home' screen upon app start.

**FR002**: The home screen shall display a list on upcoming deadlines and 'Pinned' items.

​		**FR002.1**: Upcoming deadlines shall be defined by the app as within 1 week from the current date.

​		**FR002.2**: Users shall be able to remove an item with an 'Hide' button on the corner of the item.

​		**FR002.3**: Users shall be able to open the page of the app relevant to a pinned item on the home screen 		when the user presses the item

**FR003**: A menu bar shall be displayed at the bottom of every screen in the app.

​		**FR003.1**: The menu bar shall display a home button, deadline button, study planner button, health 		list button and study tips button.

**FR004**:  When the user presses the deadline button on the menu bar, the deadline page shall be displayed.

​		**FR004.1**: The deadline page shall display a list of all deadlines that have been added by the user and stored by the system.

​		**FR004.2**: Each deadline item shall have a custom colour and display only the name and date

**FR005**: The deadline page will display a button that will open a form allowing deadlines to be added.

​		**FR005.1**: Users shall be able to set attributes including; name, subject, date, display colour, alert 				intervals and "submit" button.

​		**FR005.2** Alert intervals shall be displayed as a list of checkboxes with a set of times including; 1 month, 		2 weeks, 1 week, 3 days, 1 day, 3 hours, 1 hour, half an hour.

​		**FR005.3**: The system shall display the updated list of deadlines after form submission with "Submit" 		button

**FR006**: Pressing a deadline will bring up a page giving detailed information about the deadlines.

​		**FR006.1**: This will display the name, subject, date, display colour, alert intervals and "Finished" button.

​		**FR006.2**: The user shall be able to edit the fields described in FR007.1 and save the changes using the 		"Finished" button.

​		**FR006.3**: After pressing the submit button, the app shall show the updated deadlines display page

**FR007**: When the user presses the study timetable button on the menu bar, the study timetable shall be displayed.

​		**FR007.1**: The study timetable shall be displayed in a 5 days x 14 hours configuration.

​		**FR007.2**: The timetable shall be populated using stored information if this exists by the app.

​		**FR007.3**: The time slots of the timetable will contain a custom title only.

**FR008**: The study planner page shall display a button that will open a form allowing study slots to be added to the timetable.

​		**FR008.1**:  The form will contain fields for title, timeslot, subject, notes, a "Tags" field and a "Submit" 		button.

​		**FR008.2** The "Tags" field shall display lists of deadlines and articles from the health and study tips lists 		as the User types names of these deadlines and articles.

​		**FR008.3**: The system shall display the updated timetable after form submission with "Submit" button.

​		**FR008.4**: The system shall not display timeslot options that are already filled

**FR009**: When the User presses a study slot, the app shall bring up a page giving detailed information about the slot.

​		**FR009.1**: This will display the title, timeslot, subject, notes, a "Tags" field and a "Finished" button.

​		**FR009.2**: The user shall be able to edit the fields described in FR011.1 and save the changes using the 		"Finished" button.

​		**FR009.3**: After pressing the submit button, the app shall show the updated timetable display page.

**FR010**: The timetable page shall display an import button allowing import of existing University calendar.

​		**FR010.1**: When the User presses the import button, the app shall open a form.

​		**FR010.2**: This form shall contain fields for the calendar link, an option between Google and Apple and 		"Get calendar" button.

​		**FR010.3**: The app shall get data from calendar and add to study timetable when "Get calendar" is 			pressed, and the user shall be returned to the timetable screen.

​		**FR010.4**: If the calendar cannot be retrieved, an error message shall be displayed to users, and the 		user shall be returned to the timetable screen.

**FR011**: The timetable page shall display an export button allowing import of existing calendar

​		**FR011.1**:When the User presses the export button, the app shall open a form.

​		**FR911.2**: This form shall contain fields for the calendar name, log in information, an option between 		Google and Apple an "Export calendar" button.

​		**FR011.3**: The app shall send data to the external calendar when "Export calendar" is pressed, and the 			user shall be returned to the timetable screen with a success message displayed.

​		**FR011.4**: If the calendar cannot connected with, an error message shall be displayed to users, and the 		user shall be returned to the timetable screen.

**FR012**: Pressing the health list button on the menu bar shall display a list of health articles and information.

​		**FR012.1**: The health list shall display recipes, physical exercises and mental health information.

​		**FR012.2**: The app shall display each item as a thumbnail and a title.

​		**FR012.3**: The list shall be scrollable to accommodate items added by the server updates

**FR013**: Pressing the study tips button on the menu bar shall display a list of study information

​		**FR013.1**: These pieces of information shall be displayed by the app as thumbnails and titles.

​		**FR013.2**: The list shall be scrollable to accommodate items added by the server updates

**FR014**: The user shall be able to view the full information of a list item from  FR014 or FR015 by tapping it.

​		**FR014.1**: The user shall be able to navigate back to their last screen with a 'back' button.

**FR015**: The user shall be able to pin a list item from  FR014 or FR015 by pressing a toggle displayed on the item.

**FR016**: The user shall be able to refresh either list from FR014 or FR015 by pulling down at the top of the list.

**FR017**: Users shall be able to remove an item from either list with an 'Hide' button on the corner of the item.


### 4. Data Requirements
#### 4.1 Content data management

**FR017**: The app shall store articles from both lists in device storage for offline access

**FR018**: The app shall store new posts from either lists in device storage after list refresh

**FR019**: The post titles and thumbnail shall be stored in the app cache

**FR020**: The articles shall be stored by the system as html pages

**FR021**: The study planner and deadline files shall be stored as CSV files in device storage


### 5. External Interface Requirements
#### 5.1 Hardware Interfaces

**FR022**: The app shall be compatible with android mobile chipsets

**FR023**: The app shall read input from touch screens for all interaction

​	

#### 5.2 Software Interfaces

**FR024**: (linked to **FR010** and **FR011**):  the app will be able to interface with Google and Apple calendar, when the user imports and exports the study calendar

​		**FR024.1**: Specifically, the app shall interface with the webDAV protocol for both calendars 

**FR025**: (Linked to **FR005.2**): The app shall interface with the android alarm API when the user sets deadline alerts

​		**FR025.1**: Specifically, the app shall interface with AlarmManager.AlarmClockInfo

#### 5.3 User Interface

**FR026**: The app shall be laid out in an orientation compatible with mobile devices

​		**FR026.1**: The apps layout shall support aspect ratios of 16:10, 17:10, 16:9 in a portrait position

**FR027**: (Linked to **FR003**): The apps menu bar shall be persistent on every screen in the app



### 6. Quality Attributes
#### 6.1 Usability

**NFR001**: The app shall implement a material style UI

**NFR002**: The app shall utilise a largely monochromatic colour palette to accommodate colour blind people
