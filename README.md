This Python To-Do List program uses Tkinter for the GUI and SQLite for storing tasks.

1. Database Setup (sqlite3)
It creates a database file (to_do.db).

A table (tasks) is created to store tasks if it doesn't exist.

commit() is used to save changes.

2. Functions for Managing Tasks
a) load_tasks()
Fetches all saved tasks from the database and displays them in the list.

b) add_task()
Adds a new task from the input box to the list.

Saves the task in the database.

Prevents empty task entries.

c) delete_task()
Deletes the selected task from the list and database.

Shows a warning if no task is selected.

3. GUI Design (Tkinter)
Title & Entry Box: Users enter tasks.

Buttons: "Add Task" (Green ✅) & "Delete Task" (Red ❌).

Listbox: Displays tasks with a yellow selection highlight.

4. Running the Program
Tasks are loaded from the database on start.

GUI runs with root.mainloop().

Database connection closes when the app closes.

🔹 Outcome: A simple interactive To-Do List with task saving! ✅
