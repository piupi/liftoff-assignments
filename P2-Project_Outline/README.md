# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

---

### Overview
An alternative to typical calorie-tracking apps that focuses on logging meals with pictures.  Type the calories and take a picture, and the calorie total of the day will update.  A simple way to stay mindful of your eating habits. 
Many calorie tracking apps use the list approach, where you have to log everything in a list. My problem with those apps are that the they are not visual enough: pictures say a lot more than words! Stopping to take a picture of what you're about to eat makes you more mindful. It's a visual reminder of how you use your calories.

### Features
Current Features
* Camera: User can type the calories and take a photo. Currently works on Android phones. (On Desktop it will ask to use your webcam. iPhone does not support WebRTC API.)
* Photo grid: Photos are stored with Firebase. Each new meal gets added to the grid.
* Time: Photos are arranged by time taken. The time is displayed in the upper left corner of each meal.
* Delete: User can delete a meal.
* Date: Today's date shows at the top of the food journal.
* Total: Each time a user adds a new meal, the total calorie count of the day updates.
* Login: User login works (Firebase) but does not do anything yet. 

Future Features (First two are my goal during CoderGirl LiftOff)
* React.js: *Successfully* switch entire project to React. I have made a mess so far in my attempt to do this.
* User accounts: Set up user accounts so multiple people can use it reliably every day. Save users’ history so they can view previous days through the Calendar. 
* Calendar: The Calendar will give you the option to mark a day as "reached my goal" or "did not reach my goal", which will be highlighted in green or red on the Calendar. This will provide a visual of how you did overall that month. It’s up to the user to reflect and decide if they’ve met their goals each day, whatever that means for them. I hope this will help catch patterns in eating habits – maybe they always overeat junk food on Mondays, for example!
* Compatibility with other devices. 
* Track symptoms like migraines, bloating, etc. so you can narrow down which foods caused it.
* Improved UI showing the calorie total better, animations.
* Weight tracking?
* Eating reminders?
* Sharing your food journal?
* Storing foods you eat often for easy access?
* Search bar for calorie info of common foods?

### Technologies
* JavaScript
* HTML
* CSS
* WebRTC API
* Firebase
* React

### What I'll Have to Learn (Goals during this course)
* The most difficult part with React is how my specific project will handle State. My State is already messy as it is. I will need to find a solution for that.
* If I reach my goal of *successfully* incorporating React, I will then work on user accounts. I will need to learn how to show each user a different page.
* After that, I will need to learn how to save a user's history and only show them the current day. And allow them to go back and access older dates.

### Project Tracker
[Trello Board](https://trello.com/b/i1uZ9SaZ/vanessa-kratohvil-capstone)

[Project](https://foodjournal.netlify.app/) 
(Please **do not** delete my preloaded pictures. You can add your own picture and delete it.)

### NOTE:
I changed my mind about doing this project. I am just going to make a portfolio page for myself rather than messing with my old project.