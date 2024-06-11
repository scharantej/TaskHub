## Flask Application Design

### HTML Files

#### `index.html`
- Main HTML file that displays the timer and task list.
- Contains elements for user input (adding tasks), time display, and task management (marking as completed, etc.).

### Routes

#### `/add_task`
- Route to add a new task to the list.
- Accepts a POST request with task details, such as name, icon, and estimated time.

#### `/delete_task`
- Route to delete a task from the list.
- Accepts a POST request with the task ID to be deleted.

#### `/start_timer`
- Route to start the timer.
- Accepts a POST request from the user.

#### `/stop_timer`
- Route to stop the timer.
- Accepts a POST request from the user.

#### `/mark_completed`
- Route to mark a task as completed.
- Accepts a POST request with the task ID to be marked as completed.

#### `/get_tasks`
- Route to retrieve the list of tasks from the database.
- Returns a JSON response with the task data.

#### `/get_time`
- Route to retrieve the current time from the system.
- Returns a JSON response with the current time.