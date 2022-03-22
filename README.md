# next-day-app
React app
# Intro
This app will helps to create todo tasks for tommorow. On next day user can track there task and update the percentage of completion. they can move to completed state. they can manage task based on the schedule to manage the time. at the end of the day it will show the performence based on our task completion.

# Implementation
"/" SignUp SignIn page

"/Home" page with Calender with pointing to nextday. and disabling upcomming days.

onclick any Day goto '/task' (except future days)

performance button to get performence detail.

should show the task detail which is scheduled at current time

'/task' show Todo Tasks and completed Tasks

		here need to create drag and drop
    
		can eneter % of completion
    
		can add a slot to the task
    
		estimated time for that task
    
		task should be shown based on priority
    
		give option to add new task and delete and update task
    
		give option to get excell sheet of task of that day or week or month
		
'/add-task' should open task form.

			->task priority
      
			->task details
      
			->estimated time
      
			->time slot
      
'/update-task' should open same form with pre filled details

'/performence' should show performence based on completeion of target
