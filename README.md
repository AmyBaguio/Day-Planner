# 05 Third-Party APIs: Work Day Scheduler

Create a simple calendar application that allows the user to save events for each hour of the day. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

You'll need to use the [Moment.js](https://momentjs.com/) library to work with date and time. 


## Acceptance Criteria

GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
//// use moments.js to display date & time
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
//// create timeblocks for business hours from 9am-5pm
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
//// each color code for past(grey) - present(red) - future(green) 
WHEN I click into a timeblock
THEN I can enter an event
//// on hourly time block, can enter an event or activity
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
//// after entering event/activity, must have a "save" button to store into local storage
WHEN I refresh the page
THEN the saved events persist
//// when page is refresh, the saved event/activity persist






