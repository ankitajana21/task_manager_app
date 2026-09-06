# Task Manager

A simple **Python command-line Task Manager** that uses a priority queue and undo stack to manage tasks efficiently. Tasks can also be saved to and loaded from JSON files.

## Features

* Add, delete, and edit tasks
* Assign task status, deadline, and priority
* View all tasks
* View tasks ordered by priority
* Undo the last action
* Save tasks to a JSON file
* Load tasks from a JSON file

## Data Structures Used

* **List** — stores all tasks
* **Heap / Priority Queue** — manages tasks based on priority using `heapq`
* **Stack** — stores actions for the undo functionality
* **JSON** — provides persistent task storage

## Requirements

* Python 3.x
* No external libraries required

## Run

```bash
python taskmanager.py
```

Follow the menu displayed in the terminal to manage your tasks.

## Task Format

Each task contains:

```text
Title
Status
Deadline
Priority
```

Example:

```json
{
    "title": "Complete assignment",
    "status": "pending",
    "deadline": "2026-09-10",
    "priority": 1
}
```
