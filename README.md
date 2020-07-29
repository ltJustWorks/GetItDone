# GetItDone

Concept: A time tracking program for college and university to help you stick to your plans and be more productive.
Implementation in Python.


## Feature Goals
* Focuses on the user spending less time laying out their work plans, and more time spent actually getting work done
	* The only regular input required from the user should be starting/stopping a timer for registering the time they spend on a task and what task they're working on
* Timetable View
	* The user can compare the timetable with all the tasks they completed for a day with a timetable showing what the user wanted to work on during different blocks of time throughout the day (the user can set this up)
	* Capability of syncing timetable with Google Calendar to get notifications(?)
* Alerts
	* Alerts the user when they should start working on their next task that is set up on their timetable, records if the user did start working on the task or not
* Start Time / End Time
	* The user can set up a start time and an end time for their workday
	* The app can see if the user started their work day after their desired start time, and/or if they worked past their desired end time
* Shows the user their "productivity pulse" based on a number of factors:
	* The amount of work the user has accomplished thus far
	* The user's ability to adhere to their schedule and start time/ end time
	* Calculates a daily, weekly, and monthly productivity pulse
* Gratitude Journaling
	* Asks users to write a little reflection at the end of the day, and how they felt about the day
	* Users are shown their reflections from the past days
* Desktop app with a mobile companion

## Advanced Features
* The app can estimate how long a user will take to complete a task, based on the time they've spent completing similar tasks previously
	* The app calculates a minimum time & maximum time estimate for a task, and records if a user was able to complete the task closer to the minimum or maximum time
* Auto-generated Timetables
	* The user can create a layout for their work schedule, so that the app can automatically create new schedules based on the user's desired layout, and also the data the app has received from the user about how long certain tasks take to get finished
* Social Features
	* Users can see others' productivity pulses
