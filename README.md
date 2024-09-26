# task-manager
Description

This Task Manager is a simple web application that allows users to add and display tasks dynamically in a table format. The project uses HTML, CSS, and JavaScript to provide a basic task management interface where tasks are added one by one, and displayed in a list.
Features

    Input Field: Users can enter a task in the input field.
    Add Task Button: Clicking the "Add Task" button will add the task to the task table.
    Dynamic Table: The task table is dynamically updated with each task added.
    Validation: Users are alerted if they attempt to add an empty task.

Files Included

    index.html: This file contains the structure of the task manager, including HTML, CSS, and JavaScript.

Usage Instructions

    Open the HTML File: Open the index.html file in a web browser.

    Add a Task:
        Enter a task in the input field.
        Click the "Add Task" button to add it to the task list.
        The added task will appear in the table below.

    Input Validation:
        If the input field is empty and the "Add Task" button is clicked, an alert will notify the user to input a task.

Code Explanation

    HTML Structure:
        The page is structured with a simple <h1> title, an input field for task entry, a button to add tasks, and a table to display tasks.
        The table consists of a single column titled "Task" to list the added tasks.

    CSS Styling:
        The layout is styled using basic CSS to give the input field, button, and table a clean look. The table is formatted to have borders around the cells, with padding for better readability.

    JavaScript Functionality:
        The addTask() function is triggered when the "Add Task" button is clicked.
        It checks if the task input field is empty. If so, it alerts the user to enter a task.
        If a task is entered, it inserts the new task into the table by adding a new row dynamically using JavaScript.
        After the task is added, the input field is cleared.

How to Customize

    You can extend the functionality of this task manager by:
        Adding a delete button next to each task to allow removal.
        Storing tasks locally using localStorage to retain them after a page refresh.
        Enhancing the design with more styles for a better user interface.

License

This project is free to use and modify. No specific license applies.
