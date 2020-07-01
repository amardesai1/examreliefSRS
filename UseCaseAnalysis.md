## Use Case Analysis for ExamRelief
### Creating and viewing a deadline
##### Use case

Create and add a deadline

##### Primary Actor

- App User
  - Goal - To add a deadline to the apps interface for easy tracking and access

##### Other Actors

- App

##### Goal

This use case provides the ability for the user  to open the form on the deadline screen and create a deadline. 

##### Scope

Deadline recording functionality  of ExamRelief mobile app

##### Preconditions: 

- The app has been purchased and is installed correctly on an android touch screen device
- The user has already set up an account

##### Success condition

App has deadline stored and user can view it and receive notifications

##### Trigger

Opening the app and clicking on the deadline screens "New" deadline button.

##### Main Success scenario:

1. User opens the app
2. App opens to home screen
3. User navigates to deadline screen using menu bar
4. Deadline screen opens
5. User clicks on the '+' button under the list of deadlines
6. App opens form for adding new deadline
7. User fills out form with:
   - Deadline subject
   - Deadline name
   - Deadline date
   - Deadline colour (for display in app)
   - Deadline alert time
8. User presses 'Add' button at bottom of form
9. App adds this date to storage and returns user to deadline screen

##### Post  Conditions

- Deadline screen must be displayed
- New added deadline must be displayed on the screen
- Other deadlines must be visible if they exist
- New deadline must be sorted by date order with other deadlines
- Deadline must have been stored by app

##### Exceptions

​	8a.  Deadline date is invalid

   8a1. Error message will be displayed, form won't submit

​	8b. Name, date or colour aren't added

   8b1. User is informed that form isn't complete and form won't submit

​	8c. No alert times are added

   8c1. User is reminded to add alerts, form can be submitted anyway

​	9a. Storage writing error occurs

   9a1. User is informed and asked to restart app

​	9b. Storage is full

   9b1. User is informed that storage is full and deadline cannot be added
