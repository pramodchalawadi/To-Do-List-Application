# To-Do List Application (Console-Based)

##  Project Overview

This is a simple **console-based To-Do List application** written in Python. It allows users to:

* Add tasks
* View tasks
* Remove tasks
* Store tasks in a `tasks.txt` file for persistence

The program ensures that tasks are **saved** even after you exit and restart the application.

---

##  Features

1. **Add Task** – Add new tasks to your to-do list.
2. **View Tasks** – Display all current tasks.
3. **Remove Task** – Delete tasks by selecting their task number.
4. **Persistent Storage** – Tasks are stored in a text file (`tasks.txt`).

---

##  File Structure

```
ToDoApp/
│-- todo.py   # Main program file
│-- tasks.txt          # File where tasks are stored
│-- README.md          # Documentation
```

---

##  How to Run

1. Make sure you have **Python 3** installed.
2. Save the code into a file named `todo_list_app.py`.
3. Open your terminal or command prompt and navigate to the project folder.
4. Run the script:

   ```bash
   python todo.py
   ```

---

##  Example Usage

**Program Start:**

```
--- To-Do List Menu ---
1. View Tasks
2. Add Task
3. Remove Task
4. Exit
Choose an option (1-4):
```

**Adding a Task:**

```
Enter a new task: Buy groceries
Task added successfully!
```

**Viewing Tasks:**

```
Your To-Do List:
1. Buy groceries
2. Complete Python assignment
```

**Removing a Task:**

```
Enter the task number to remove: 1
Task 'Buy groceries' removed successfully!
```

**Exit:**

```
Exiting... Goodbye!
```

---

##  tasks.txt File Example

After adding two tasks, the `tasks.txt` file will look like this:

```
Buy groceries
Complete Python assignment
```

---



 Developed with  in Python.
