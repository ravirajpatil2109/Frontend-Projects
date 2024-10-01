# Task Tracker

## Overview
This is a simple **Task Tracker** application built using **JavaScript**. The application allows users to manage a to-do list by adding new tasks, marking them as completed, and deleting tasks. Completed tasks move to the bottom of the list with a strikethrough. Users can also unmark tasks to return them to the pending list.

## Screenshot
![Task Tracker Screenshot](https://github.com/user-attachments/assets/dd868d92-a4b4-44ef-8db1-7e55a187205e)

## Features
- Add new tasks to the to-do list.
- Mark tasks as completed.
- Unmark completed tasks.
- Delete tasks.
- Completed tasks are moved to the bottom of the list with a strikethrough.
- Real-time dynamic rendering of tasks using JavaScript.

## How it works
Tasks are stored in an array of objects, where each object represents a task with properties like:
- `description`: A string representing the task.
- `status`: A boolean representing whether the task is completed or not.

The `renderTasks` function updates the DOM whenever tasks are added, marked as complete, unmarked, or deleted.

## Technologies Used
- HTML
- CSS
- JavaScript

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ravirajpatil2109/task-tracker.git

2. **Open the project**: Open `index.html` in your browser to see the Task Tracker in action.


## Future Enhancements

- Add due dates and priority levels for tasks.
- Implement a filter for viewing only completed or pending tasks.
- Add task categories or tags.

## Contributing

Feel free to contribute to this project by opening a pull request or raising an issue.
