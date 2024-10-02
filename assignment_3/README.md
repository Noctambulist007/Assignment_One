# Assignment 3

# Task Manager App

A Flutter task management application that allows users to create, categorize, and prioritize their tasks.

# ScreenShot

<img width="390" alt="Screenshot 2024-10-02 at 7 18 06 PM" src="https://github.com/user-attachments/assets/d37bef3b-5a3c-4b14-9d70-0fdee904c259">


## Features

- **Task Creation**: Users can create tasks with the following attributes:
  - Title
  - Description
  - Due Date
  - Priority (1-5)
  - Tags (Comma-separated)
  - Automatic categorization (Work, Personal, Shopping, Urgent)
  
- **Task Listing**: View all tasks in a list format.
  - Tasks are displayed with title, description, due date, priority, and category.

- **Task Categorization**: Tasks are automatically categorized based on their description using a regex-based system:
  - Work, Personal, Shopping, Urgent

- **Add Task Button**: A floating action button to quickly create new tasks.

- **Bottom Sheet**: Task creation form opens in a stylish modal bottom sheet.

