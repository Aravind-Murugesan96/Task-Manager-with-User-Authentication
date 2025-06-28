## Task Manager with User Authentication
A simple Python project in Jupyter Notebook that allows multiple users to register, log in, and manage their tasks independently. This project demonstrates user authentication, file-based storage, and task CRUD operations in an interactive notebook environment.

## Overview
This Task Manager enables users to:
  Register securely with a username and password
  Log in to their account
  Add, view, complete, and delete tasks
Passwords are hashed using SHA-256 for basic security. All user credentials and tasks are saved as text files so data persists between sessions.

## Features
User Registration and Login
  - Secure password storage with hashing
  - Authentication from stored credentials
Task Management
  - Add new tasks
  - View all tasks and their statuses
  - Mark tasks as completed
  - Delete tasks by ID
Persistent Storage
  - users.txt stores registered users
  - tasks_<username>.txt stores tasks per user

## How to Run in Jupyter Notebook
download Task Manager with User Authentication.ipynb from repository : https://github.com/Aravind-Murugesan96/Task-Manager-with-User-Authentication
Launch: Jupyter Notebook
Open: Task Manager with User Authentication.ipynb
Run each cell in order: Cells define functions and run the main loop interactively
Follow the prompts in the notebook output

## Project Structure
task-manager-auth-jupyter/
├── Task Manager with User Authentication.ipynb
├── users.txt                # Auto-created to store user credentials
├── tasks_<username>.txt     # Auto-created per user to store tasks

## Example usage:
===== Task Manager =====
1. Register
2. Login
3. Exit
Enter your choice: 1
Enter a username: alice
Enter a password: ****
Registration successful!

===== Task Manager =====
1. Register
2. Login
3. Exit
Enter your choice: 2
Enter your username: alice
Enter your password: ****
Login successful!

1. View Tasks
2. Add Task
3. Mark Task as Completed
4. Delete Task
5. Logout

## Conclusion
This project is an educational example of:
  Using Jupyter Notebook for interactive development
  Managing users and tasks with Python
  Persisting data without a database

Ideal for beginners to learn authentication, file handling, and building console applications inside Jupyter.
