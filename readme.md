# Task Manager

This is a simple web application that allows users to manage tasks. Users can add, update, and delete tasks. Each task has a title, date, and description.

## Features

- Add Task: Users can add a new task by entering a title, date, and description in the task form.
- Update Task: Users can update an existing task by editing the title, date, and description in the task form.
- Delete Task: Users can delete a task by clicking the "Delete" button on the task card.
- Confirm Close: If the task form contains unsaved changes, a dialog will appear to confirm whether the user wants to close the form and discard the changes.

## How It Works

The application uses JavaScript to manipulate the DOM and handle user interactions.

- `addOrUpdateTask()`: This function adds a new task or updates an existing task based on the values in the task form. It updates the tasks in the local storage and the tasks container, and resets the task form.
- `updateTaskContainer()`: This function updates the tasks container to display all tasks in the local storage.
- `deleteTask(buttonEl)`: This function deletes a task when the "Delete" button on the task card is clicked. It updates the tasks in the local storage and the tasks container.
- `editTask(buttonEl)`: This function populates the task form with the values of a task when the "Edit" button on the task card is clicked. It changes the text of the "Add Task" button to "Update Task" and shows the task form.
- `reset()`: This function resets the task form and hides it.

## How to Use

1. Open the HTML file in a web browser.
2. Click the "Add Task" button to show the task form.
3. Enter a title, date, and description in the task form and click the "Add Task" button to add a new task.
4. Click the "Edit" button on a task card to update the task.
5. Click the "Delete" button on a task card to delete the task.

## Future Improvements

- Add a search bar to filter tasks by title.
- Add a date picker to select the date for a task.
- Improve the user interface for a better user experience.