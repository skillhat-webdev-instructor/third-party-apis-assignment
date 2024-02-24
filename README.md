# Assignment : Working with Third Party APIs: Creating a Task Board

Edward Apostol, for Skillhat, January 2024

## Summary

You assignment is to create a simple task board application that allows a team to manage project tasks by modifying starter code. 

This app will run in the browser and will feature dynamically updated HTML and CSS powered by jQuery as observed in your lessons. *Do not use native JavaScript methods such as document.createElement(), appendChild() etc.*

You'll need to explore and utilize a second third party API / library called Day.js [https://day.js.org/en/](https://day.js.org/en/) - https://day.js.org/en/ to work with dates. 

Be sure to review the documentation for both Day.js as well as JQuery ([https://api.jquery.com/](https://api.jquery.com/)) to ensure your application will work in the browser.

## User Story

A *user story* is a description of the task to complete  written in a manner that can be communicated to non-technical personnel such as managers and clients.

```md
AS A project team member with multiple tasks to organize
I WANT a task board 
SO THAT I can add individual project tasks, manage their state of progress 
and track overall project progress accordingly
```

## Acceptance Criteria

The *acceptance criteria* is written in a form of sentence structure known as *gherkin* syntax that outlines the physical requirements of the steps required to perform the task, again written in a way that most non-technical people could read and understand.

```md
GIVEN a task board to manage a project
WHEN I open the task board

THEN the list of project tasks is displayed in columns representing the task progress state 
(Not Yet Started, In Progress, Completed)

WHEN I view the task board for the project
THEN each task is color coded to indicate whether it is nearing the deadline 
(yellow) or is overdue (red)

WHEN I click on the button to define a new task
THEN I can enter the title, description and deadline date for the new task into a modal dialog

WHEN I click the save button for that task
THEN the properties for that task are saved in localStorage

WHEN I drag a task to a different progress column
THEN the task's progress state is updated accordingly and will stay in the new column after refreshing

WHEN I click the delete button for a task
THEN the task is removed from the task board and will not be added back after refreshing

WHEN I refresh the page
THEN the saved tasks persist
```

The following animation below demonstrates the application functionality. You can view the animated gif directly by clicking this [animated image](./Assets/05-third-party-apis-homework-demo.gif) 

![A user adds three tasks to the task board and changes the state of two of them to in progress and then completion. The user then deletes the two cards in the done column.](./Assets/05-third-party-apis-homework-demo.gif)

## Grading Requirements

This Challenge is graded based on the following criteria:

### Technical Functionality: 40%

* Satisfies all of the above acceptance criteria plus the following:

  * Uses the Day.js library to work with dates

### Deployment: 32%

* Application deployed at live Github Pages URL

* Application loads with no errors

* Application GitHub Repository URL submitted

* GitHub Repository contains application code

### Application Usability / Interaction: 15%

* Application user experience is intuitive and easy to navigate

* Application user interface style is clean and polished

* Application resembles the mock-up functionality provided in the Challenge instructions

### Repository Standards: 13%

* Created a new repository for this assignment and has a unique name

* Repository follows best practices for file structure and naming conventions

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages

* Repository contains quality README file with description, screenshot, and link to deployed application

* It is suggested to link your completed github pages website and repository link to your portfolio site as well.

## Review

You are required to submit the following for review in Google Classroom - *Please do not email your submission in, as the email will not get checked as often.*

* The URL of the deployed application

* The URL of the GitHub repository, with a unique name and a README describing the project`
