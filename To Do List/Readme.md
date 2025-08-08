HTML
Exercise - Build To Do List HTML
Let us now build the entire HTML / CSS for our project based on our knowledge so far.
Note that once we learn DOM events/ OOPs / User Input in Javascript, we will make some changes to our HTML.
Task 1
Add the title 'To-Do List App' to your HTML
Within the body, create a div with class named "container"
Within the div, add the heading 'To-Do List' using the <h1> tags


Exercise - Build To Do List HTML
Let us create the user input container to hold the Task, its deadline date and a button to add the task to one of our lists.
Task 2
Within the class "container", do the following
Create a new div with class as "input-container"
Inside the "input-container" div, create 2 user input boxes and a button
The 1st input box should have the following
Type - 'text'
id - 'taskInput'
Placeholder - 'Enter task...'
The 2nd input box should have the following
Type - 'date'
id - 'deadlineInput'
The button element should have the following
Give an id of addButton to it.
Name the button as 'Add'


Exercise - Build To Do List HTML
Let us now add the 2 separate blocks for the 'High Priority Tasks' and the 'Low Priority Tasks'.
Task 3
Within the class "container", do the following
Create a new div with id as "todoList"
Include the text as - 'High Priority Tasks:'
Create a div with id as "highPriorityContainer". This id will help us in the styling for this block of high priority tasks
Include the text as - 'Low Priority Tasks:'
Create a div with id as "lowPriorityContainer". This id will help us in the styling for this block of high priority tasks


CSS
Exercise - Build To Do List HTML
Time for beautifying the webpage.
Let's code out the CSS.
Task 4
In the style.css file, add the following properties
For the <h1> tag
Center the text 'To-do List'
Set margin-top as 0
For the "container" class, set the following
max-width as 550px
margin as 20px auto
background-color as #fff
padding as 20px
border-radius as 5px

Exercise - Build To Do List HTML
Let us now focus on the user-input container.
Let's code out the CSS.
Task 5
In the style.css file, add the following properties
For the "input-container" class
Set its display as 'flex'
For the "input- container" class with input type, set the following
Set flex-grow as 1
Set padding as 10px
Set border-radius as 10px
Set font-size as 16px
For the "input- container" class with type button, set the following
background-color as #4caf50;
color as #fff
border-radius as 3px
padding as 10px 20px
margin-left as 10px
cursor as pointer
font-size as 16px
transition as background-color 0.3s ease

Exercise - Build To Do List HTML
Let us now focus on the 2 sections containing the High priority and Low priority rasks.
Let's code out the CSS.
Task 6
In the style.css file, add the following properties
For the "highPriorityContainer" and "lowPriorityContainer" IDs, set the following
border-radius as 5px
height as 200px
width as 90%
margin as 10px
padding as 10px
Specifically for the Id "highPriorityContainer", set border as 3px solid red
Specifically for the Id "lowPriorityContainer", set border as 3px solid brown