# Classroom Cleaning Monitor

## Overview

Classroom Cleaning Monitor is a browser-based dashboard for assigning and tracking classroom cleaning tasks. It is implemented as a single HTML file with CSS and JavaScript.

## Features

- Add a student and cleaning task.
- Search tasks by student name or task description.
- Filter tasks by All, Pending, or Completed.
- Mark tasks as Complete or Undo them.
- Edit both the student name and task.
- Delete tasks with confirmation.
- Reset the default demo roster.
- View task totals and completion progress.
- Automatically save tasks in the browser using `localStorage`.

## How to Run

1. Open `index.html` in a web browser.
2. Enter a student name and cleaning task, then select **Add Task**.
3. Use the table buttons to complete, edit, or delete tasks.
4. Use the search field and status filters to narrow the task list.

## File Structure

- `index.html` - Application markup, styles, and JavaScript.
- `README.md` - Project documentation.
- `promt_log.md` - Record of development prompts and changes.

## Storage

Tasks are stored in the browser under the `cleaningTasks` local storage key. Clearing browser site data removes saved tasks.
