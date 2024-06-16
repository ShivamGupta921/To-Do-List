# To-Do List

This is a simple console-based To-Do List application written in C++. It allows users to add, view, modify, and remove tasks. The tasks are stored in a binary file and each task has a unique task number, a task description, and a completion status.

## Features

1. **Add Task**: Allows you to add a new task to the list.
2. **Show Tasks**: Displays all the tasks along with their status (completed or not completed).
3. **Manage Tasks**: Allows you to check/uncheck tasks to mark them as completed or not completed.
4. **Remove Tasks**: Allows you to remove specific tasks, remove all completed tasks, or clear the entire list.
5. **Exit**: Exits the application.

## How to Use

### Adding a Task

1. Select option `1` from the main menu.
2. Enter the task description.
3. The task will be added to the list with a unique task number and an initial status of not completed.

### Viewing Tasks

1. Select option `2` from the main menu.
2. All tasks will be displayed with their task number, status, and description.
3. Completed tasks are marked with `[✓]`, and not completed tasks are marked with `[ ]`.

### Managing Tasks

1. Select option `3` from the main menu.
2. The list of tasks will be displayed.
3. Enter the task number to toggle its completion status.
4. Enter `0` to return to the main menu.

### Removing Tasks

1. Select option `4` from the main menu.
2. The list of tasks will be displayed.
3. Enter the task number to remove a specific task.
4. Enter `-1` to remove all completed tasks.
5. Enter `-2` to remove all tasks.
6. Enter `0` to return to the main menu.

### Exiting the Application

1. Select option `5` from the main menu.
2. The application will exit.

## Dependencies

- The application uses the `<iostream>`, `<fstream>`, `<string.h>`, `<cstdlib>`, `<cstdio>`, and `<iomanip>` libraries.

## Compilation and Execution

### Compilation

To compile the application, use a C++ compiler such as `g++`:

```sh
g++ -o todo todo.cpp
```

### Execution

To run the compiled application:

```sh
./todo
```

## File Storage

- The tasks are stored in a binary file named `tasks.dat`.
- A temporary file `temp.dat` is used during the removal of tasks.

## Notes

- Make sure to have appropriate permissions to create, read, write, and delete files in the directory where the application is run.
- The application clears the console screen using `system("cls")`, which is platform-specific to Windows. If you're using a different operating system, replace it with the appropriate command (e.g., `system("clear")` for Unix-based systems).

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software.

## Author

This application was created by Shivam Gupta as part of an internship in App Development at Bharat Intern.

---

Feel free to reach out with any questions or suggestions!
