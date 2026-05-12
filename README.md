# Task-Scheduler
# Task Scheduler using C++

A simple Task Scheduler built using C++ and the STL `priority_queue` data structure.
The program allows users to add tasks with different priorities, display tasks sorted by priority, and execute the highest-priority task first.

---

## Features

* Add tasks with custom names
* Assign priorities from 1 to 10
* Automatically sort tasks using a Priority Queue
* Display all tasks in priority order
* Execute and remove the highest-priority task
* Input validation for invalid priorities

---

## Technologies Used

* C++
* STL Priority Queue
* Structures (`struct`)
* Functions
* Custom Comparator using `operator()`

---

## How It Works

The project uses a `priority_queue` with a custom comparator to ensure that tasks with higher priorities are processed first.

### Main Operations

1. Add Task
2. Show All Tasks
3. Execute Highest Priority Task
4. Exit Program

---

## Example

```text
Welcome to the Task Scheduler

1) Add task
2) Show tasks
3) Execute highest priority task
4) Exit

Enter task name:
Finish Assignment

Enter task priority:
9
```

---

## Concepts Practiced

* Object-oriented thinking
* Data structures
* Priority Queue implementation
* STL containers
* Custom comparators
* Input validation
* Function modularity

---

## Future Improvements

* Save tasks to files
* Add deadlines and dates
* GUI version
* Task categories
* Task completion history

---

## Author

Ibrahim Gamal

GitHub Repository:
[https://github.com/ibrahimgamal765lt/Task-Scheduler](https://github.com/ibrahimgamal765lt/Task-Scheduler)
